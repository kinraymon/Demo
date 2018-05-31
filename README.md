DEMO
===========================
###环境依赖

node v0.10.28+<br>
reids ~

###部署步骤
####1.添加系统环境变量

    export $PORTAL_VERSION="production" // production, test, dev


####2.npm install  //安装node运行环境<br>
####3.gulp build   //前端编译<br>
####4.启动两个配置(已forever为例)

    eg: forever start app-service.js<br>
        forever start logger-service.js


###目录结构描述

    ├── Readme.md                   // help<br>
    ├── app                         // 应用<br>
    ├── config                      // 配置<br>
    │   ├── default.json<br>
    │   ├── dev.json                // 开发环境<br>
    │   ├── experiment.json         // 实验<br>
    │   ├── index.js                // 配置控制<br>
    │   ├── local.json              // 本地<br>
    │   ├── production.json         // 生产环境<br>
    │   └── test.json               // 测试环境<br>
    ├── data<br>
    ├── doc                         // 文档<br>
    ├── environment<br>
    ├── gulpfile.js<br>
    ├── locales<br>
    ├── logger-service.js           // 启动日志配置<br>
    ├── node_modules<br>
    ├── package.json<br>
    ├── app-service.js              // 启动应用配置<br>
    ├── static                      // web静态资源加载<br>
    │   └── initjson<br>
    │   	└── config.js 		// 提供给前端的配置<br>
    ├── test<br>
    ├── test-service.js<br>
    └── tools<br>



###V1.0.0 版本内容更新

    1. 新功能	 aaaaaaaaa<br>
    2. 新功能	 bbbbbbbbb<br>
    3. 新功能	 ccccccccc<br>
    4. 新功能	 ddddddddd<br>
