# Node demo
用于学习Node的基础操作和koa框架

#### 目录结构

```
NodeDemo
│  .gitignore
│  package-lock.json
│  package.json
│  README.md
├─koa
│  ├─koa_mvc
│  │  │  app.js
│  │  │  controller.js
│  │  └─controllers
│  │          hello.js
│  │          login.js
│  ├─koa_normal
│  │      koa_cookie.js
│  │      koa_error.js
│  │      koa_http1.js
│  │      koa_http2.js
│  ├─koa_rest
│  │  │  app.js
│  │  │  controller.js
│  │  │  product.js
│  │  │  rest.js
│  │  │
│  │  └─controllers
│  │          api.js
│  │          index.js
│  └─koa_sql
│          app.js
│          config.js
│          init.txt
│          seq.js
└─node_base
        crypto.js
        http_demo.js
```

#### 目录简介
- koa_normal: koa框架的基础操作（Cookie、错误处理、http等等）
- koa_mvc: 以koa框架为基础的MVC结构web服务器
- koa_rest: 以koa框架为基础的REST服务器
- koa_sql: 在koa框架下对数据库的操作
- node_base: node下的基础操作