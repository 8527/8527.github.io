---
layout: post
title: how to use markdown
date: 2018-09-20
categories: blog
tags: [markdown]
description: how to use markdown

---

一、标题的语法
===

1、第一种
---

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

2、第二种（只支持一级和二级标题；=、-的个数没有限制，大于一个就好）
---

一级标题
===
二级标题
---

3、第三种
---

# 一级标题 #
## 二级标题 ##
### 三级标题 ###
#### 四级标题 ####
##### 五级标题 #####
###### 六级标题 ######

二、 列表的语法
===
1、无序列表
---
* 1
* 2
* 3
+ 1
+ 2
+ 3
- 1
- 2
- 3

2、有序列表
---
1. 有序列表1
2. 有序列表2
3. 有序列表3

三、 区块引用的语法
===

1、对某个部分说明或引用
---

* 人生苦短，我用python
    > Guido van Rossum

2、 引用中可以放标题、列表、引用
---

> ## python
> * python是最好的语言
>   >大家都这么觉得

3、引用嵌套（理论上可以无限嵌套）
---

> 一级引用
>> 二级引用
>>> 三级引用
>>>> 四级引用
>>>>> 五级引用
>>>>>> 六级引用
>>>>>>> 七级引用

四、 分割线
===

分割线可以由* - _（星号，减号，底线）这3个符号的至少3个符号表示，注意至少要3个，且不需要连续，有空格也可以
---

***
* * *
---
- - -
___
_ _ _


五、链接 
===

1、 行内式
---
[百度一下](http://www.baidu.com)

2、参数式（[]中的参数不支持中文）
---
[name]:http://www.baidu.com/name "名称"
[home]:http://www.baidu.com/home "首页"
我的名字是[name],这里是[home]

3、带链接的列表
---
* [百度](http://www.baidu.com)


六、图片
===

1、行内式
---
![python](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1537508666337&di=70142a6c6bc7e4df8d59ed5c4920617a&imgtype=0&src=http%3A%2F%2Fdownza.img.zz314.com%2Fedu%2Fpc%2Fbcgj-1054%2F2017-07-14%2F32a134411beae675a06db1d02b2a9838.png)

2、参数式
---
[python]:https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1537508666337&di=70142a6c6bc7e4df8d59ed5c4920617a&imgtype=0&src=http%3A%2F%2Fdownza.img.zz314.com%2Fedu%2Fpc%2Fbcgj-1054%2F2017-07-14%2F32a134411beae675a06db1d02b2a9838.png
参数式图片，这里是![python]

七、表格
===

1、第一种（分割线后面的冒号表示对齐方式，写在左边表示左对齐，右边为右对齐，两边都写表示居中）
---
| name| age | sex |
|---:|:---:|:---|
|jack |  20 |  男 |
|tony |  30 |  男 | 

2、第二种（默认左对齐）
---

name | age | sex
-----|-----|-----
jack |  20 | 男

八、强调
===
*字体倾斜*
_字体倾斜_
**字体加粗**
__字体加粗__

九、删除线
===
~~删除线~~

十、代码区
===

1、多行代码
---
```打印helloworld(这里是注释)
def main()：
    print('helloword!')
 if __name__==__main()__:
    main()
```
2、单行代码
---
`print('helloworld!')`