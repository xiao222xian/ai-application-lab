# AI 图片生成页面实验 | AI image-generation page experiment

此目录保留 Ark 图片生成页面及其轻量 Node 服务原型，包含生图、重新生成和保存交互。请先检查 `package.json` 与源码以了解具体实现。本次没有执行依赖安装、调用外部模型或验证生成效果。

This folder preserves a prototype Ark image-generation page and lightweight Node service, with generate, regenerate, and save interactions. Review `package.json` and source files for implementation details. Dependencies were not installed, and no external model calls or output validation were performed during curation.

原型曾采用浏览器直接调用服务的方式。浏览器代码不能保密服务密钥；不要在前端源码或静态资源中放入真实 Key。用于实际应用时，应由后端代理请求、保护密钥并实施访问控制。

The prototype used a browser-side service call. Browser code cannot keep service keys secret; never place a real key in frontend source or static assets. For a real application, route requests through a backend that protects the key and enforces access controls.
