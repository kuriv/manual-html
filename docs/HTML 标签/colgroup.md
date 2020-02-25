# colgroup

> colgroup 标签用于对表格中的列进行组合，以便对其进行格式化。

语法：

```html
<table>
    <colgroup>
        <col span="2" style="background-color:red">
        <col style="background-color:yellow">
    </colgroup>
    <tr>
        <th>ISBN</th>
        <th>Title</th>
        <th>Price</th>
    </tr>
    <tr>
        <td>3476896</td>
        <td>My first HTML</td>
        <td>$53</td>
    </tr>
</table>
```

效果：

<table>
    <colgroup>
        <col span="2" style="background-color:red">
        <col style="background-color:yellow">
    </colgroup>
    <tr>
        <th>ISBN</th>
        <th>Title</th>
        <th>Price</th>
    </tr>
    <tr>
        <td>3476896</td>
        <td>My first HTML</td>
        <td>$53</td>
    </tr>
</table>