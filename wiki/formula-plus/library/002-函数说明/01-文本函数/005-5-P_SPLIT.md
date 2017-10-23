# P_SPLIT函数

## 说明

根据指定分割符，拆分文本内容，并返回指定位置的内容。

## 语法

**P_SPLIT(txtRange, splitter, [get_index], [returnType])**

- txtRange：要拆分的文本
- splitter：分隔符
- get_index：拆分完成后，要提取第几个文本内容，默认为第1个。支持倒数索引，如果填写-1，则返回最后一个拆分结果。
- returnType：返回的类型，有3种类型。
  - 如果=0（默认），则返回[get_index]对应的字符。
  - 如果=1，则返回[get_index]左侧的所有字符。
  - 如果=-1，则返回[get_index]右侧的所有字符。

## 返回值

返回提取出来的内容。

## 案例

1- 根据顿号，把一段文字，拆分到列单元格中

![](http://mypic.ladeng6666.com/2017-05-19-split1.gif)

2-根据顿号，把多行文字，一次性拆分到列单元格中

![](http://mypic.ladeng6666.com/2017-05-19-split2.gif)

3- 多列内容，转成一列

![](http://mypic.ladeng6666.com/2017-05-19-split3.gif)

4- 根据顿号，提取最后一个字段

![mark](http://mypic.ladeng6666.com/blog/171023/Ge0khGfaIF.gif)

5- 根据顿号，删除最后一个字段

![mark](http://mypic.ladeng6666.com/blog/171023/6DGEjmKCe3.gif)