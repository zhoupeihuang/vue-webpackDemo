
**webpack与vue起步**
=============
----------

vue-webpackDemo
---------------

主要记录的是**webpack 和 vue2.0**的整合 无任何其他东西 不包括vuex and vueRoute
项目启动 先 npm install 
当前 前提是你已经安装了 共享的 webpack webpack-dev-server vue vue-cli
**cnpm install -g webpack webpack-dev-server vue vue-cli**
*-g 是共享目录*
因为package.json内已经配置好了 需要的module and plugin 所以 只需
**cnpm  install  --save-dev** 
安装完成后
只需要**npm start** 即可启动[start--已经修改成了 *webpack -p*压缩模式]


附录


# 全局安装webpack，webpack-dev-server

 1. $ npm install -g webpack
 2. $ npm install -g webpack-dev-server

# 为项目安装其他依赖

 1. $ npm i webpack-merge css-loader style-loader file-loader url-loader
    babel-core babel-loader babel-plugin-transform-runtime
    babel-preset-es2015 babel-preset-stage-0 babel-runtime vue
    vue-loader vue-html-loader vue-style-loader vue-hot-reload-api -D


解释

 1. webpack-merge：开发环境和生产环节的webpaak配置文件的配置合并
 2. css-loader：编译写入css
 3. style-loader：把编译后的css整合进html
 4. file-loader：编译写入文件，默认情况下生成文件的文件名是文件名与MD5哈希值的组合
 5. vue：vue主程序
 6. vue-laoder：编译写入.vue文件
 7. vue-html-loader：编译vue的template部分
 8. vue-style-loader：编译vue的样式部分
 9. vue-hot-reload-api：webpack对vue实现热替换
 10. babel-core：ES2015编译核心
 11. babel-loader：编译写入ES2015文档
 12. babel-preset-es2015：ES2015语法
 13. babel-preset-stage-0：开启测试功能
 14. babel-runtime：babel执行环境

参考案例

webpack与vue起步 http://mrzhang123.github.io/2016/05/31/webpack-vue-2/
