# pjax无刷新封装

> 1. [配置：](#配置： "配置：")
> 2. [用法：](#用法： "用法：")

>   1. [js:](#js: "js:")
>   2. [html:](#html: "html:")

<br>

## 配置：

```javascript

shim: {
  'pajax': ['pjax'],
},
paths: {
  pjax: './package/pajax/jquery.pjax',
  pajax: './package/pajax/pajax',
}
```

## 用法：

### js:

```javascript
pajax.initModule('main', function () {}, function (targetelement, state) {
  //回调函数 搭配router 实现mvc
});
```

### html:

```html
//关闭无刷新
<a href="#"></a>
```
