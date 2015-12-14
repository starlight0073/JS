## main dependencies
- **react**
  创建用户界面的 JavaScript 库
- **react-dom**
  针对DOM的 JavaScript 库 基于 react
- **redux**
  是 JavaScript 状态容器，提供可预测化的状态管理。可以让你构建一致化的应用，运行于不同的环境（客户端、服务器、原生应用），并且易于测试。
- **react-redux**
  将react 和 redux 两个 JavaScript 库 绑定起来
  
## middleware
- **redux-thunk**
  	用最简单的方式搭建异步 action 构造器

## dev dependencies
- **babel-core**
  我们要基于ES6开发应用，目前的浏览器暂不完全支持所有新语法特。我们可以使用`转译器`，帮助我们将ES6代码转译为主流浏览器支持的ES5代码。Babel.js不仅支持ES6语法，它还可以编译JSX
- **babel-loader**
  提供各种资源`加载器`
- **babel-plugin-react-transform**
  任意的方式去组装react 组件
- **react-transform-hmr**
  模块热替换（Hot Module Replacement）
- **mocha**
  测试引擎
- **react-addons-test-utils**
  用于测试react components
- **redux-devtools**
  一个使用时间旅行 UI 、热加载和 reducer 错误处理器的 action 日志工具
- **webpack**
>	1. 同时支持CommonJS和AMD模块（对于新项目，推荐直接使用CommonJS）；
> 	2. 串联式模块加载器以及插件机制，让其具有更好的灵活性和扩展性，例如提供对CoffeeScript、ES6的支持；
>	3. 可以基于配置或者智能分析打包成多个文件，实现公共模块或者按需加载；
>	4. 支持对CSS，图片等资源进行打包，从而无需借助Grunt或Gulp；
>	5. 开发时在内存中完成打包，性能更快，完全可以支持开发过程的实时打包需求；
>	6. 对sourcemap有很好的支持，易于调试。

	Webpack将项目中用到的一切静态资源都视之为模块，模块之间可以互相依赖。Webpack对它们进行统一的管理以及打包发布

- **webpack-dev-middleware**
- **webpack-hot-middleware**


## PS：
CommonJS和AMD是用于JavaScript模块管理的两大规范，前者定义的是模块的同步加载，主要用于NodeJS；而后者则是异步加载，通过requirejs等工具适用于前端