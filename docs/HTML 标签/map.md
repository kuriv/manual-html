# map

> map 标签用于客户端图像映射，图像映射指带有可点击区域的一幅图像。

语法：

```html
<img src="planets.jpg" alt="planets" usemap="#planets">

<map name="planets">
    <area shape="rect" coords="0,0,110,260" href="planets_sun.gif" alt="Sun">
    <area shape="circle" coords="129,161,10" href="planets_merglobe.gif" alt="Mercury">
    <area shape="circle" coords="180,139,14" href="planets_venus.gif" alt="Venus">
</map>
```

效果：

<img src="planets.jpg" alt="planets" usemap="#planets">

<map name="planets">
    <area shape="rect" coords="0,0,110,260" href="planets_sun.gif" alt="Sun">
    <area shape="circle" coords="129,161,10" href="planets_merglobe.gif" alt="Mercury">
    <area shape="circle" coords="180,139,14" href="planets_venus.gif" alt="Venus">
</map>