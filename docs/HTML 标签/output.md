# output

> output 标签作为计算结果输出显示。

语法：

```html
<form oninput="x.value = parseInt(range.value) + parseInt(number.value)">
    0<input type="range" id="range" value="50">100
    +
    <input type="number" id="number" value="50">
    =
    <output name="x">100</output>
</form>
```

效果：

<form oninput="x.value = parseInt(range.value) + parseInt(number.value)">
    0<input type="range" id="range" value="50">100
    +
    <input type="number" id="number" value="50">
    =
    <output name="x">100</output>
</form>