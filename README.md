知乎日报 - Vue 2.0 版本
------

~~FakeZhihu~~  Vue-Zhihu
---

~~**Note: I am going to build zhihu via Vue, but this version is still the base, nothing changed yet!**~~

## 后端

后端只是一个express框架的代理转发服务器，将请求转发到知乎的服务器上。

## 前端

前端使用vue2.0搭建的SPA，整合了axios、vuex、vue-router等库，采用webpack（2.x版）打包，前端静态页面没有服务端渲染。


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
