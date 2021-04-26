# xlsx

> 在线预览excel

## 1、部署注意事项
``` bash
## 需要将此项目部署到和excel文件所在的同一个域下，否则无法实现预览
```

## 2、正确打开方式

``` bash
## 打开当前项目的同时，使用?作为分隔符，使用data作为参数，值为excel的url地址

如：
## 当前项目：scheme://domain/index.html
## excel文件： scheme://domain/xxx/xxx/abcd.xlsx

正确示例：
scheme://domain/index.html?data=scheme://domain/xxx/xxx/abcd.xlsx

```
