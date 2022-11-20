# vue-3-github-page-template


## - 주의

Node 18 버전에서 실행되지 않는 경우가 있었습니다.
Node 16.16.0 버전에서 실행 확인하였습니다.

## - example page

[https://arkimcity.github.io/vue-3-github-page-template](https://arkimcity.github.io/vue-3-github-page-template)


## - new project

frontend\vue.config.js

```javascript
const path = require("path");
module.exports = {
  outputDir: path.resolve(__dirname, "../docs"),
  publicPath: process.env.NODE_ENV === 'production'
    ? '/vue-3-github-page-template/' // this is going to be your new subdomain url for github pages
    : '/'
}

```

## - run test

from root

```
cd frontend

npm run serve
```


## - build

from root

```
cd frontend

npm run build
```
