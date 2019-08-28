# 硅谷外卖（后端）

## 前端项目
**[硅谷外卖（前端）](https://github.com/duganlx/gshop-client)**

## 环境搭建
- Mongodb安装
- 下载ide工具，如WebStorm
- 依赖下载  
 
## 项目运行
 > 1.编码测试  
 > - npm run dev  
 > - 测试[接口文档](https://github.com/duganlx/gshop-server/blob/master/API%E6%96%87%E6%A1%A3.md)中的接口

## 项目结构分析
```text
gshop-server
    |-- api: 与前台交互模块文件夹
        |-- ajax.js: ajax请求函数模块
    |-- bin: 服务器配置文件夹
        |-- www.js: 服务器相关配置
    |-- data: 数据
        |-- index_category.json: 商店分类数据 json
        |-- shops.json: 商店数据 json
    |-- db: DAO层
        |-- models.js: 操作数据库模块
    |-- public: 静态资源文件夹
        |-- images: 图片资源文件夹
            |-- nav: 导航栏图片资源文件夹
            |-- shop: 商店图片资源文件夹
        |-- javascripts: 外部js文件文件夹（空）
        |-- stylesheets: 外部css文件文件夹
            |-- style.css: 样式文件
    |-- routes: 路由器文件夹
        |-- index.js: 接口功能实现模块
        |-- users.js: user接口请求实现模块
    |-- util: 工具类文件夹
        |-- sms.util.js: 容联云平台短信发送工具类
    |-- views: VIEW层
        |-- error.ejs
        |-- index.ejs
    |-- .gitignore: git版本管制忽略的配置
    |-- API文档: 接口文档
    |-- app.js: 入口js
    |-- package.json: 应用包配置文件
    |-- README.md: 应用描述说明的readme文件
```

## 项目说明
- 短信验证接口  
-- 该接口使用[容联云平台](https://www.yuntongxun.com/?ly=sem-baidu&qd=pc-dasou&cp=ppc&xl=null&kw=10236399&bd_vid=7049829319436477490)短信功能
