### Markdown两个疑问
---
多行表格可以不借助`<br>`标签么？

|序号|内容|
|:--:|:--:|
|01  |a<br>b<br>c|

类似这种？  
另外，Markdown语法支持直接声明合并表格么？  

<table>
  <tr>
    <td>序号</td>
    <td>内容</td>
  </tr>
  <tr>
    <td rowspan='3'>01</td>
    <td>a</td>
  </tr>
  <tr>
    <td>b</td>
  </tr>
  <tr>
    <td>c</td>
  </tr>
</table>
