#字体

**这是加粗的文字**
_这是倾斜的文字_`
**_这是斜体加粗的文字_**
~~这是加删除线的文字~~

# 图片链接

![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg '区块链')

# 超链接，不支持新开

[简书](http://jianshu.com)
[百度](http://baidu.com)

#超链接，支持新开
<a href="超链接地址" target="_blank">超链接名</a>

#列表

- 列表内容

* 列表内容

- 列表内容

注意：- + \* 跟内容之间都要有一个空格

1. 列表内容
2. 列表内容
3. 列表内容

注意：序号跟内容之间要有空格

- 列表内容
  - 列表内容
  - 列表内容
  - 列表内容
  - 列表内容

#表格

| 表头 |       表头       |             表头 |
| ---- | :--------------: | ---------------: |
| 内容 | 第二行告诉我剧中 | 第二行告诉我靠右 |
| 内容 |       内容       |             内容 |

第二行分割表头和内容。

- 有一个就行，为了对齐，多加了几个
  文字默认居左 -两边加：表示文字居中 -右边加：表示文字居右
- 注：原生的语法两边都要用 | 包起来。此处省略

# 流程图

````flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
````
