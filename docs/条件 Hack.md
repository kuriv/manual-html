# 条件 Hack

* [是否](#是否)
* [大于](#大于)
* [大于或等于](#大于或等于)
* [小于](#小于)
* [小于或等于](#小于或等于)
* [非指定版本](#非指定版本)
* [条件编译](#条件编译)

## 是否

语法：

```html
<!--[if IE]>
    <p>Now you see me.</p>
<![endif]-->
```

## 大于

语法：

```html
<!--[if gt IE 8]>
    <p>Now you see me.</p>
<![endif]-->
```

## 大于或等于

语法：

```html
<!--[if gte IE 8]>
    <p>Now you see me.</p>
<![endif]-->
```

## 小于

语法：

```html
<!--[if lt IE 8]>
    <p>Now you see me.</p>
<![endif]-->
```

## 小于或等于

语法：

```html
<!--[if lte IE 8]>
    <p>Now you see me.</p>
<![endif]-->
```

## 非指定版本

语法：

```html
<!--[if ! IE 8]>
    <p>Now you see me.</p>
<![endif]-->
```

## 条件编译

> 由于以上条件注释语句只支持到 Internet Explorer 9，所以如果希望能够被 Internet Explorer 10 所识别，可以使用以下条件编译语句。条件编译语句是 Internet Explorer 10 及较早版本的 Internet Explorer 所特有，因此可用于判断是否除 Internet Explorer 11 以外的其他 Internet Explorer 浏览器。

语法：

```html
<script type="text/javascript">
    /*@cc_on document.writeln('Now you see me.'); @*/
</script>
```

