1. 调试需要鼠标悬浮或者某些特定触发的样式，可以借助setTimeout(() => {debugger}, 3000)页面冻结大法。
2. 在iframe区域无法触发clickOutside关闭悬浮窗口时，可以借助window.onblur，原理是本身页面与iframe不是同一个window。
