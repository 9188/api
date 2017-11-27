
# [h5-vue](http://gitlab.gs.9188.com/caiyi.html5.public/h5-vue)




## 介绍

该模板基于 vue @2.5.2 + webpack @3.6.0  
组件库 [mint-ui](http://mint-ui.github.io/#!/zh-cn)

## 特点




## 目录结构
    
    ├── build                       - webpack 配置 （不动）
    |
    ├── config                      - webpack 配置 全局变量（可改动）
    │
    ├── dist                        - 通过编译生成的目录
    │
    ├── src                         - 项目入口
    │   ├── assets                  - 静态图片
    │   ├── common                  - 公共方法
    │       ├── ajax.js             - axios 请求类
    |       ├── fetch.js            - fetch 请求类可以和上面二选一
    │       ├── util.js             - 工具类
    │   ├── components              - 木偶组件库集合
    │   ├── constant                - 不常变的
    │       ├── api.js              - 整站接口列表
    |       ├── config.js           - 网站可配置的
    │       ├── localKey.js         - key集合
    │   ├── pages                   - 网页集合
    │       ├── xxx                 - 
    |           ├── img             - 当前页面用到的图片
    |           ├── subpage         - 当前页面用到的智能组件
    |               ├── xxx.vue     - 当前页面的子组件
    │           ├── index.vue       - 
    │   ├── router                  - 路由
    │   ├── static                  - 静态的
    │       ├── css                 - 基本css
    |           ├── common.styl     - 网站通用样式
    │           ├── mixin.styl      - 网站通用混合宏
    │
    ├── .babelrc                    - babel 配置文件
    │
    ├── .editorconfig               - VsCode 代码风格配置 配合 eslint 用很好
    │
    ├── .postcssrc.js               - postcss 插件配置文件
    │
    ├── .gitignore                  - 
    │
    ├── .eslintrc.js                - 代码风格检查配置文件
    │
    ├── index.html                  - 
    │
    ├── package.json                - 
    │ 
	└── README.md                   -     


