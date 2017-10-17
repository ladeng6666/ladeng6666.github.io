# P_TEXTJOIN函数

## 说明

使用指定的分割符，把区域中的文本连接起来。

## 语法

**P_TEXTJOIN(range,splitter, [ignoreBlank], ignoreRepeat], [actionForMerge], columnFirst)**

- range：要合并的区域。
- spliter：要使用的间隔符，如逗号，注意用引号包裹起来。
- ignoreBlank=0：是否忽略空格，默认为0不忽略，1为忽略。
- ignoreRepeat=0：是否忽略重复值，默认为0不忽略，1为忽略。
- actionForMerge=0：对于合并单元格的处理方法，默认为0不处理，1取合并格左上角数值。
- columnFirst=1：合并方式，默认为:1先合并列，再合并行，0先合并行，再合并列。

## 返回值

根据参数设定的条件，返回提取出来的内容。

## 案例1 合并多列内容

![](http://mypic.ladeng6666.com/2017-05-08-P_TEXTJOIN.gif)

使用第3个参数，可以忽略合并单元格中的空白，引用上方非空单元格中的内容。