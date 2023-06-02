# Vercel 部署服务应用



这是 [Vercel 部署 Node 服务](https://blog.azhubaby.com/2022/05/06/2022-05-06-vercel%E9%83%A8%E7%BD%B2node%E6%9C%8D%E5%8A%A1/) 文章中的demo，分别部署静态服务和 Koa 服务

静态服务预览地址： https://vercel-sample-ten.vercel.app/

Koa 服务预览地址：https://vercel-koa2-t511069160.vercel.app



有人直接 fork 项目，发现运行不了，因为不是这样搞的

`vercel-koa2` 是服务端项目，vercel 支持[无服务器函数结合使用](https://vercel.com/docs/concepts/functions/serverless-functions/runtimes/node-js#)，同样的官网有 [
将 Express.js 与 Vercel 一起使用](https://vercel.com/guides/using-express-with-vercel) 的教程

`vercel-sample` 常规的静态页面的部署
