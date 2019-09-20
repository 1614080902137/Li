## 配置读取资源文件（.css、.js）
* /config/index.js
```
build: {
  ...
  assetsPublicPath: '/项目名/'
  ...
}
```
## 配置路由
* /router/index.js
```
const route = new Router({
  ...
  base: '/项目名'
})
