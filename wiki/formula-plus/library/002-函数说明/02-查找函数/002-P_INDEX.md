# P_INDEX函数

## 说明

对于等距离间隔的数据，进行快速汇总。

比如在下面这个表单中，每一个“工程量编号”的间距都是一样的，需要汇总成右侧的样子。

![](http://mypic.ladeng6666.com/2017-06-26-232959.jpg)

## 语法

P_LOOKUP(reference1, reference2, index)

- reference1：参考地址1，既要汇总的第1个数据。
- reference2：参考地址2，既要汇总的第2个数据。
- index：要查找这个等间距数据总的第几个。

具体如下图所示：

![](http://mypic.ladeng6666.com/2017-06-26-233334.jpg)

## 返回值

返回等距离数据中，指定索引位置的数据。

## 案例

1- 返回横向等距离数据，并进行汇总

![](http://mypic.ladeng6666.com/2017-06-26-P_index.gif)

2- 返回纵向等距离数据，并进行汇总

![](http://mypic.ladeng6666.com/2017-06-26-P_index2.gif)