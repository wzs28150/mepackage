# me框架插件库

各个插件介绍

### photoswiper
>配置：
```
paths: {
   photoswipe: './package/photoswiper/photoswipe.min',
   photoswipeui: './package/photoswiper/photoswipe-ui-default.min',
   photo: './package/photoswiper/index',
}
shim: {
   'photoswipe': ['css!./package/photoswiper/photoswipe.css', 
   'css!./package/photoswiper/default-skin/default-skin.css'] 
}

```

>用法：
>js:

```
require(['photo'], function (photo) {
   photo('.demo-gallery');
});

```

>html:
```
<span class="bg demo-gallery">
<a data-ajax="no" href="./src/images/20170628023654306.png" 
data-size="1600x1600" 
data-med="./src/images/20170628023654306.png" 
data-med-size="1024x1024"  class="demo-gallery__img--main">
<img src="./src/images/20170628023654306.png" alt="" />
</a>
<a data-ajax="no" href="./src/images/20170628023654306.png" 
data-size="1600x1600" 
data-med="./src/images/20170628023654306.png"
data-med-size="1024x1024"class="demo-gallery__img--main">
<img src="./src/images/20170628023654306.png" alt="" />
</a>
</span>

```