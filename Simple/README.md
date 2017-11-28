# [simple](http://gitlab.gs.9188.com/caiyi.html5.public/simple)




## 介绍

该模板基于 gulp @3.9.1   

## 功能
> 图片压缩  
> js压缩  
> css压缩 加prefix sass编译  
> 热编译 热更新  
> js css 文件版本控制  
> ...



## 目录结构
```
|-xxx                   (项目名称)
    |-build             gulp 配置文件
    |–dist              **发布环境**（编译自动生成的）
        |–css           样式文件(style.css style.min.css)
        |–img           图片文件(压缩图片\合并后的图片)
        |–js            js文件(main.js main.min.js)
        |–index.html    静态页面文件(压缩html)
    |-rev               **manifest.json 文件 用来管理版本**
    |–src               **开发环境**
        |–css           sass文件
        |–img           图片文件
        |–js            js文件
        |–index.html    静态文件
    |–gulpfile.js       gulp配置文件
    |–package.json      依赖模块json文件,在项目目录下执行 npm install 
```