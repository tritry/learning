#### h标签标题
---
# h1
## h2
### h3
#### h4
##### h5
###### h6

---
#### 无序，有序列表
无序列表

* a
* b
* c

嵌套无序列表

* a
  * a1
    * a11
      * a111
    * a12
  * a2
* b

有序列表

1. a
2. b
3. c

---
#### 文本格式相关

*斜体一个符号*  
**粗体两个符号**  
***粗斜体三个符号***  
文本换行在文本后加两个空格，会被解释为`<br>`

也可以选择多空一行，会被解释为`<p>`

>大于号用于引用

#### 代码相关格式
行内代码使用\`\`符号，如\`\<script\>alert("Hello World!");\</script\>\`  
效果`<script>alert("Hello World!");</script>`  
如果需要打印无法输出字符则需要使用转义字符\\，如\\\<br\\\>，输出\\则需要输入\\\\  
多行代码使用  
\`\`\`语言名  
\`\`\`  
如  
\`\`\`java  
代码  
\`\`\`  
效果如下  
```java
public static void main(String[] args) {
    System.out.println("Hello World!");
}
```

#### 超链接和图片
好像有点跑题了，代码部分莫名的就变成了教程  
[原网页跳转链接](http://blog.pppploi8.me/)  
![图片](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png)  
[![带图链接](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png)](https://www.baidu.com/)  

#### 表格和选项框

|   | A | b |
|:-:|:-:|:-:|
|1  |a1 |b1 |
|2  |a2 |b2 |

- [ ] 选项1
- [x] 选项2
