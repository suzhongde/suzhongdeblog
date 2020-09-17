---
title: markdown写作语法
date: 2020-09-08 21:25:28
tags: 语法
categories: markdown
---

Typora 编辑器 ————书写即为美学
===========
官方网站:https://www.typora.io/
支持平台:

 * Windows
 * Linux
 * OSX

特点:

* 完美支持Github 的 Markdown 语法
* 人性化的书写方式:
  * 表格的书写，挪动
  * 图片，超链接，网页表格复制
  * 目录生成
* 支持 LeTex 公式书写;
* 支持Flowchart,Maermaid 等流程图绘制;
* emoji,高亮，备注，上标等书写;
* 生成网页，pdf，图片，甚至 word ，LeTex 等格式

基本的带快捷键的 Markdown 书写演示
---------------------

`Ctrl 0` 到`Ctrl 4 `：普通文本，一级~四级标题;

1

# 2

## 3

### 4

#### 5

`Ctrl B`：加粗，加粗测试；

**拉拉**

`Ctrl I`：斜体，斜体测试；

*哈哈*

`Ctrl U`：下划线，下划线测试；

<u>呵呵</u>

`Shift Alt 5`：删除线，删除线测试；

~~嘿嘿~~

`Shift Ctrl Tab键上面那个键`：行内代码块，行内代码块测试；

`11111`

`Ctrl K`：超链接，超链接测试；还支持文章内锚点，请`Ctrl`点击此处→[第二节](#基本的带快捷键的 Markdown 书写演示)；

[aaa](https://taobao.com)

`Ctrl T`：表格，支持拖拽移动，网页端表格复制转换：



| 数据一 | 数据二 |   标题   |
| :----: | :----: | :------: |
|  943   |  baka  | 表格测试 |

> a
>
> > b

`Ctrl Shift Q`：引用：

>我需要三件东西：爱情，友谊和图书。然而这三者之间何其相通！
>
>炽热的爱情可以充实图书的内容，图书又是人们最忠实的朋友。

`Shift Ctrl I`：图片：

![风景](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1599330423615&di=2826ee091d03a1deaa3a96c861709164&imgtype=0&src=http%3A%2F%2Fattach.bbs.miui.com%2Fforum%2F201408%2F24%2F150506tvs8u3iwomt3m4db.jpg )

![胡歌](https://bkimg.cdn.bcebos.com/pic/5fdf8db1cb134954d3dd657a584e9258d0094ae9?x-bce-process=image/resize,m_lfit,h_500,limit_1 )

1



`Shift Ctrl M`：公示块，快捷输入 LeTex 公式：


```python
#hello
print('hello world!')
```

```python
#!/ysr/bin/python3
import os
with open('List.txt','w') as f:
    for i in range(10):
        f.writelines(str(i))
    print('成功写入数列')
os.system('rm ./List.txt')
print('成功删除文件')
```

* 001
  * 0002
    * 003

无序，有序，任务列表：

* 酒石酸菌
* 玄墨之蝶



- [x] 001
- [ ] 002



1. HTML
2. Python3



- [x] 1.12.2 教程计划
- [x] Weblate翻译计划
- [ ] All The Mods 3实况计划



参考链接：

​	通过培养实验研究了有机酸对铅，镉的毒害影响，结果表明柠檬酸对铅[^1]，酒石酸对镉有较明显解毒作用[^2]

。用逐步提取法研究萝卜内重金属存在的化学形态，有机酸处理并不影响各形态铅的优势顺序，但各形态铅

的浓度或相对百分率发生了变化[^3]。



[^1]: 陈苏，污染土壤中镉，铅的活化及植物有效性研究[D],中国科学院沈阳应用生态研究所，2007.
[^2]: 陈英旭，林琦，陆芳，等，有机酸对铅，镉值株危害的解读作用研究[J]。环境科学学报，2000，20（4）：467-472
[^3]: laizhiyu



上标下标:

```
上标：X^2^
下标：H~2~O
```

X^2^,H~2~O

X^6^

H~2~O



高亮：

```
本节课重点：==第六，七章不考==，第三章出题较多，--平时分占 30%==
```

本节课重点：==第六，七章不考==，第三章出题较多，==平时分占30%==

==本段不考==

注释：

```
<!--这一段不要显示出来-->
```

<!--这一段不要显示出来-->

$e^2$



内联公式:

```
$e^{i\pi}+1=0$
```

$e^{i\pi}+1=0$



----



分割线:

```
----
```

我绝不会弃坑的！	

----

:arrow_up:上面的都是假话

:arrow_up:

emoji图标：

```
:arrow_heading_down: :arrow_heading_up
:ab: :blue_heart: :jack_o_lantern:
:ballot_box_with_check: :fork_and_knife:
```

:arrow_heading_down::arrow_heading_up:

:ab::blue_heart::jack_o_lantern:

:ballot_box_with_check::fork_and_knife:



[TOC]





目录生成：

```
[toc]
```



[TOC]


# Markdown 拓展功能

HTML 原生支持，目前只支持 img 标签，用以自定义图片大小和缩放：

```
<img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1599396637179&di=b102d6f9f779568ab4ae90d5d00fbeac&imgtype=0&src=http%3A%2F%2Fpic.rmb.bdstatic.com%2F2ef2f7ae08aa741552212a6bb8468d03.jpeg" width="550px" alt="test"></img>
```

<img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1599396637179&di=b102d6f9f779568ab4ae90d5d00fbeac&imgtype=0&src=http%3A%2F%2Fpic.rmb.bdstatic.com%2F2ef2f7ae08aa741552212a6bb8468d03.jpeg" width="550px" alt="test"></img>



LeTex 公式支持，包括 mhchem，AMSmath，BBox：

mhchem：

AMSmath：

BBox：

流程图支持，内置 Flowchart，Sequence，Mermaid引擎，支持多种多样的流程图，时序图，甘特图：

* 流程图（Flowchart）

* ```flow
  ​```flow
  st=>start: 开始框
  op=>operation: 处理框
  cond=>condition: 判断框(是或否?)
  sub1=>subroutine: 子流程
  io=>inputoutput: 输入输出框
  e=>end: 结束框
  st->op->cond
  cond(yes)->io->e
  cond(no)->sub1(right)->op
  ​```
  ```

* 流程图（Mermaid）

```mermaid
​```mermaid
graph LR
A[方形] -->B(圆角)
    B --> C{条件a}
    C -->|a=1| D[结果1]
    C -->|a=2| E[结果2]
    F[横向流程图]
​```
```



* 时序图（Mermaid）

```sequence
​```sequence
对象A->对象B: 对象B你好吗?（请求）
Note right of 对象B: 对象B的描述
Note left of 对象A: 对象A的描述(提示)
对象B-->对象A: 我很好(响应)
对象A->对象B: 你真的好吗？
​```
```



* 甘特图（Mermaid）

```mermaid
​```mermaid
%% 语法示例
        gantt
        dateFormat  YYYY-MM-DD
        title 软件开发甘特图
        section 设计
        需求                      :done,    des1, 2014-01-06,2014-01-08
        原型                      :active,  des2, 2014-01-09, 3d
        UI设计                     :         des3, after des2, 5d
    未来任务                     :         des4, after des3, 5d
        section 开发
        学习准备理解需求                      :crit, done, 2014-01-06,24h
        设计框架                             :crit, done, after des2, 2d
        开发                                 :crit, active, 3d
        未来任务                              :crit, 5d
        耍                                   :2d
        section 测试
        功能测试                              :active, a1, after des3, 3d
        压力测试                               :after a1  , 20h
        测试报告                               : 48h
​```
```

* 其他 Mermaid 图（目前还有点问题，不建议使用）
* Class diagram

```mermaid

```



* Git

```mermaid

```





# 主题替换

访问：http://theme.typora.io/

# 文章导出

* 图片（非常适合手机阅读）
* PDF
* HTML（可选择是否带样式表）
* 其他需要第三方支持




