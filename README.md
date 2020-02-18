# [markdown 语法](#)

# 一
## 二
### 三
#### 四
##### 五
###### 六
一般
**粗体**
*斜体*
***
* 1
- 2
1. 一
***
![桌面](http://upload-images.jianshu.io/upload_images/15296591-7ceb1a67726153c9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
[百度链接](https://www.baidu.com)
***
```
for i in range(10):
    if i <= 8:
        print(i)
    else:
        break
```
    print("hello world")
***
| 水果        | 价格    |  数量  |
    |  :-   | -----:   | :----: |
    | 香蕉      | $1      |   5    |
    | 苹果        | $1      |   6    |
    | 草莓        | $1      |   7    |
>表格转自：[Gaolex](https://www.jianshu.com/u/9bd3ba22210c)

# sublime markdown
[Sublime Text3 的 Markdown 实时预览全面总结](https://blog.csdn.net/qq_20011607/article/details/81370236)

# xpath
```
from lxml import etree
text = """
<p> hello world </p>
<p> hello world1 </p>
<p> hello world2 </p>
<p> hello world3 </p>
"""
html = etree.HTML(text)  # 初始化
p0 = html.xpath('//p')
print(etree.tostring(p0[0]).decode("utf-8"))

\>>><p>hello world</p>

```
