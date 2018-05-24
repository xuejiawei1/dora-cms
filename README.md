# doracms 2.0.5

![DoraCMS](http://7xkrk4.com1.z0.glb.clouddn.com/doracms2.jpg "DoraCMS")

## 2.0.5版本更新
1、用户中心添加文章功能，用户可以发布文章了，支持markdown语法

2、优化webpack打包流程，压缩lodash，拆分element-ui

3、服务端异常处理

4、用户留言xss处理

5、修复文章点击量不准确的问题

6、修复在开发环境下，后台切换登录超级管理员和测试管理员，左侧菜单没有变化的问题

7、首页添加了用户留言模块，以及推荐模块

演示地址： [前端开发俱乐部](https://www.html-js.cn)
后台登录： https://www.html-js.cn/dr-admin     测试账号：doracms/123456

开发文档： [前端内容管理框架 DoraCMS2.0 开发文档](https://www.html-js.cn/details/ryn2kSWqZ.html)   
生产部署教程： [DoraCMS2.0 linux部署(生产环境)教程](https://www.html-js.cn/details/ry4-B-hkf.html)  


## 目录结构

```
├─build // webpack 相关配置文件
│
├─configs // 配置文件
│  │  
│  └─logConfig.js  // 日志配置文件
│ 
├─logs // 日志目录
│
├─dist  // webpack 生成文档存放目录
│  │
│  ├─server
│  │
│  └─static
│      ├─css
│      │
│      ├─images
│      │
│      ├─img
│      │
│      └─js
│
├─server    // 服务端目录
│  │
│  ├─lib    // 核心层
│  │
│  └─routes // 路由文件
│
├─src           // 客户端程序目录
│  │
│  ├─api        // api 配置文件
│  │
│  ├─filters    // 过滤器
│  │
│  ├─index      // 前台组件
│  │
│  ├─manage     // 后台组件
│  │
│  ├─template   // 初始模版
│  │
│  └─utils      // 实用工具
│
└─utils
    ├─middleware // 中间件
    │
    ├─authPower.js // 资源鉴权
    │
    ├─authSession.js // session 鉴权
    │
    ├─authToken.js // token鉴权
    │
    ├─logUtil.js // 日志配置
    │
    ├─settings.js // 关键信息配置
    │
    └─validatorUtil.js // 信息校验

```

首页
http://localhost:8080  
http://35.194.153.183:8080

登录
http://localhost:8080/dr-admin  
http://35.194.153.183:8080/dr-admin
