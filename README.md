# web书城阅读器部分

## 技术栈
   zepto + promise + ajax + 本地存储

## 运行
   下载后需启动本地服务器
    
## 逻辑
1. 页面的图标使用base64格式的图片
   * 用`window.jQuery = $`使zepto代替jquery，能够方便使用jquery的插件 
2. 交互部分实现了点击显示菜单，字体缩放，背景切换，夜间模式等功能。
   * 主要利用localstorage存储章节信息，背景索引，字体大小等信息
3. 模拟服务端以及回调分别采用了回调函数和ES6的promise两种方式
