# 目录
[toc]

# 块元素
# 1号字体
## 2号字体
### 3号字体
#### 4号字体
##### 5号字体
###### 6号字体

> 段落1：This is a blockquote with two paragraphs. This is first paragraph.
>
> 段落2：This is second pragraph. Vestibulum enim wisi, viverra nec, fringilla in,laoreet vitae, risus.
>
>
>
>段落3：This is another blockquote with one paragraph. There is three empty line to
>seperate two blockquote.

## 列表：数据库
1. MySQL
2. Oracle
3. PostgreSQL

## 列表：语言
* Java
* C
* C++

## 任务列表：选择题
- [x] A
- [ ] B
- [ ] C
- [x] D

## 数学公式
* 使用MathJax渲染LaTeX数学表达式
$$
\mathbf{V}_1 \times \mathbf{V}_2 = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} & \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} & \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$


## 表格
| 洲际 | 国家 | 首都 |
| --- | --- | ---|
| 亚洲 | 中国 | 北京 |
| 欧洲 | 法国 | 巴黎 |

## 脚注
You can create footnotes like this[^footnote].

.[^前脚注]  ABC  [^后脚注].  Here is the *斜体* of the **粗体**.

## 分割线
***
---

# 跨度元素

## 超链接

.[^ inline link]百度一下，你就知道！ [百度](http://www.baidu.com/)

.[^reference]  [BaiDu][]  And then define the link:

[BaiDu]: http://baidu.com/

## URLs
* 直接插入链接/以链接方式显示出来
<lujun@cmhi.chinamobile.com>
<https://www.baidu.com>

## 图片

![这是一个图片](C:\disk_c\图像\毛笔字\砥砺前行.jpg)

## 文字变形：斜体/*号
*single asterisks*
_single underscores_
\*this text is surrounded by literal asterisks\*
~~横线~~
<u>下划线</u>
:smile:
==highlight==.

## 加粗
**加粗字体**
__加粗字体__

## 代码
~~~java
import java.util.Scanner;
public class ScannerTest {
    public static void main(String[] args){
        Scanner scanner=new Scanner(System.in);
        System.out.print("请输入一个数");
        int a=scanner.nextInt();
        System.out.printf("%d的平方是%d\n",a,a*a);
    }
}
~~~

~~~python
import random    
if __name__ =="__main__":    #四位数字字母验证码的生成
    checkcode="" #保存验证码的变量
    for i in range(4):
        index=random.randrange(0,4)  #生成一个0~3中的数
        if index!=i and index +1 !=i:
            checkcode +=chr(random.randint(97,122))  # 生成a~z中的一个小写字母
        elif index +1==i:
            checkcode +=chr(random.randint(65,90) ) # 生成A~Z中的一个大写字母
        else:
            checkcode +=str(random.randint(1,9))  # 数字1-9
    print(checkcode)
~~~

## 特殊字符
版权： &copy;
注册商标： &reg;
商标： &trade;
空格： &nbsp;
和号： &amp;
引号： &quot;
撇号： &apos;
小于号： &lt;
大于号： &gt;
不等号： &ne;
小于等于： &le;
大于等于： &ge;
分： &cent;
磅： &pound;
欧元： &euro;
元： &yen;
节： &sect;
乘号： &times;
除号： &divide;
正负号：&plusmn;




