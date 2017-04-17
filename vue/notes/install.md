# Vue.js学习日记

## npm安装相关

**安装cnpm**
- 使用淘宝镜像 npm install -g cnpm --registry=https://registry.npm.taobao.org
- 优势：包下载速率较快
- 参考：[http://www.runoob.com/nodejs/nodejs-npm.html](http://www.runoob.com/nodejs/nodejs-npm.html)

**安装vue**
1. cnpm install vue
2. cnpm install --global vue-cli
    - Vue.js提供的一个官方命令行工具
    - 提供了开箱即用的构建工具配置
    - 只需几分钟即可创建并启动一个带热重载、保存时静态检查以及可用于生产环境的构建配置的项目
3. vue init webpack testVue
    - 创建一个基于 webpack 模板的新项目
    - webpack 是模块打包工具：它做的事情是，分析你的项目结构，找到JavaScript模块以及其他的一些其他一些浏览器不能直接运行的拓展语言（Scss，TypeScript等），并将其打包成合适的格式以供浏览器使用
    - vue-router 是Vue的路由插件，它是一种路径与组件之间的一种映射关系的设置
    - ESLint 是QA代码工具 用来避免低级错误和统一代码的风格。
    - Mocha 是一个js的测试框架。
    - Karma 是提供为测试框架准备运行环境，可以让这些测试在真正的浏览器运行
    - NightWatch 是一种E2E(end to end 端对端)的测试框架，端对端的测试将尽可能从用户的视角，对真实系统的访问行为进行仿真。使用Selenium WebDriver API 以将Web应用测试自动化
4. 参考：[https://cn.vuejs.org/v2/guide/installation.html](https://cn.vuejs.org/v2/guide/installation.html)



