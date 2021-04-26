# xlsx

> 在线预览excel

``` bash
## 将项目部署到excel文件存放的服务器域名下。确保该项目和要预览的excel url在同一个域下。否则无法预览

## 小翼 本地执行
npm run dev --xiaoyi-cn-test

## 小新 本地执行
npm run dev --xiaoxin-cn-test
```

## build params of deployer (部署人员关注)

``` bash
## docker 通用化打包命令
npm run build

## moli BR
npm run build moli-br-test # 测试环境
npm run build moli-br-pre # 预发布环境
npm run build moli-br-prod # 正式环境

## moli IN
npm run build moli-in-test # 测试环境
npm run build moli-in-pre # 预发布环境
npm run build moli-in-prod # 正式环境

## moli us
npm run build moli-us-test-inner #研发环境 232
npm run build moli-us-test # 测试环境 198
npm run build moli-us-pre # 预发布环境
npm run build moli-us-prod # 正式环境

## moli uk
npm run build moli-uk-test # 测试环境
npm run build moli-uk-pre # 预发布环境
npm run build moli-uk-prod # 正式环境

## moli anz
npm run build moli-anz-test # 测试环境
npm run build moli-anz-pre # 预发布环境
npm run build moli-anz-prod # 正式环境

## moli las
npm run build moli-las-test # 测试环境
npm run build moli-las-pre # 预发布环境
npm run build moli-las-prod # 正式环境

## 小翼 cn
npm run build xiaoyi-cn-test # 测试环境
npm run build xiaoyi-cn-pre # 预发布环境
npm run build xiaoyi-cn-prod # 正式环境

## 小新 cn
npm run build xiaoxin-cn-test # 测试环境
npm run build xiaoxin-cn-pre # 预发布环境
npm run build xiaoxin-cn-prod # 正式环境

## lena 测试环境
npm run build lena-in-test # IN UK CAP/ANZ US
npm run build lena-las-test # LAS
npm run build lena-jp-test # JP

## lena 预发布环境
npm run build lena-in-pre-inner # IN UK CAP/ANZ US
npm run build lena-in-pre # IN UK CAP/ANZ US
npm run build lena-las-pre # LAS
npm run build lena-jp-pre # JP

## lena 生产环境
npm run build lena-in-prod # IN
npm run build lena-las-prod # LAS
npm run build lena-jp-prod # JP
npm run build lena-uk-prod # UK
npm run build lena-cap&anz-prod # CAP/ANZ
npm run build lena-us-prod # US

```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
