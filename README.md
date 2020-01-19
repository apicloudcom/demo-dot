#展示 doT 模板主要用法

当我们动态生成一个数据列表、复杂详情页等时，如果使用字符串拼接的方式会加大很多工作量。同时页面显示效果也可能出现闪动等现象。
推荐开发者使用在 webkit 浏览器引擎下效率比较高的 js 模板插件 doT.min.js。

##这个示例演示了如何以 doT.min.js 实现输出、循环、条件判断等。
* 示例请使用 Apploader 查看。

##开发指南

**调用示例**

```js
var template = document.getElementById('template');
var templateContent = template.innerHTML;
var dotTemplate = doT.template(templateContent);
listDiv.innerHTML = dotTemplate(data);
```

* 推荐文档([http://olado.github.io/doT/index.html](http://olado.github.io/doT/index.html))
* 推荐文档([https://github.com/olado/doT/tree/master/examples](https://github.com/olado/doT/tree/master/examples))
