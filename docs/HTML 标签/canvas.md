# canvas

> canvas 标签是一个画布标签，必须通过使用脚本来绘制图形。

语法：

```html
<canvas id="testCanvas"></canvas>

<script type="text/javascript">
    var testCanvas = document.getElementById('testCanvas');
    var canvasContext = testCanvas.getContext('2d');
    canvasContext.fillStyle = '#FF0000';
    canvasContext.fillRect(0,0,80,100);
</script>
```

效果：

<canvas id="testCanvas"></canvas>
<script type="text/javascript">
    var testCanvas = document.getElementById('testCanvas');
    var canvasContext = testCanvas.getContext('2d');
    canvasContext.fillStyle = '#FF0000';
    canvasContext.fillRect(0,0,80,100);
</script>