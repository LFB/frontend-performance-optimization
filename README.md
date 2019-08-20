## 学习背景
刚做前端时，我面试时被问到：从浏览器输入一个 URL 会发生什么？

现在来回答这个问题，我以现在的水平回答也觉得很难，我上网翻阅了非常多关于此问题的资料，我惊叹着这个知识系统如此庞大，我发现了顺着这个知识脉络，可以把前端的知识点也能够系统学习，比如开始进行 dns解析得到IP，dns解析那么慢如何优化？设置缓存，设置dns prefetch，得到了IP后进行TCP连接，TCP连接每次都需要进行三次握手的耗时，如何优化？设置长连接，预连接，接入 SPDY 协议，TCP连接完成后进行HTTP请求，HTTP请求这块前端可以减少一些HTTP请求或请求体积，后端设置强缓存，协商缓存优化等，后端处理完后HTTP响应发回请求数据，前端工程师这里才是真正的发挥实力，比如涉及资源加载优化、服务端渲染、浏览器缓存机制的利用、DOM 树的构建、网页排版和渲染过程、回流与重绘的考量、DOM 操作的合理规避等等，这也涉及到了HTML，CSS，和JavaScript的一些底层渲染机制

## 学习大纲
- [文章：DNS预解析 »](https://github.com/liangfengbo/frontend-performance-optimization/issues/1)
