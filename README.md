# Small-stone-memories
小程序的自学过程
/** 
  属性             类型            必填          描述
  pages           String Array     是         设置页面路径
  window          Object           否         设置默认页面的窗口表面
  tabBar          Object           否         设置底部 tab 的表现
  networkTimeOut  Object           否         设置网络超时时间
  debug           Boolean          否         设置是否开启debug模式

*/
//app.json 文件用来对微信小程序进行全局配置，决定页面文件的路径、窗口表现、设置网络超时时间、设置多tab等。

********************   组件   ********************
注意：所有组件与属性都是小写，以连字符-连接
所有组件都有的属性：
id --------- String --- 唯一标示
class ------ String --- 组件的样式类，在对应的 WXSS 中定义的样式类
style ------ String --- 组件的内联样式
hidden ----- Boolean -- 组件是否显示
data-* ----- Any ------ 自定义属性，组件上触发的事件时，会发送给事件处理函数
bind* / catch* --- EventHandler -----组件你的事件

基础组件分为七大类:
一、视图容器(View Container)
  1.View(视图容器)
    属性：
    hover-class -- String -- 指定按下去的样式类
    hover-stop-propagation -- Boolean -- 默认值：false -- 指定是否阻止本节点的父节点出现点击态
    hover-start-time -- Number -- 默认值：50 -- 按住后多久出现点击态，单位毫秒
    hover-stay-time -- Number -- 默认值：400 -- 手指松开后点击态保留时间，单位毫秒
  2.scroll-view(可滚动视图容器)
    属性：
  3.swiper(滑块视图容器)

二、基础内容(Basic Content)
  1.icon(图标)
  2.text(文字)
  3.progress(进度条)

三、表单（Form）
  1.button(按钮)
  2.form(表单)
  3.input(输入框)
  4.checkbox(多项选择器)
  5.radio(单项选择器)
  6.picker(列表选择器)
  7.picker-view(内嵌列表选择器)
  8.slider(滚动选择器)
  9.switch(开关选择器)
  10.label(标签)

四、导航（Navigation）
  navigator(应用链接)

五、多媒体（Media）
  1.audio(音频)
  2.image(图片
  3.video(视频)

六、地图（Map）
  map(地图)

七、画布（Canvas）
  canvas(画布)