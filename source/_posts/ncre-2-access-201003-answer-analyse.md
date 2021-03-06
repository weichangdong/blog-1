title: 2010年3月计算机二级Access考试答案解析
tags:
  - Access
  - 真题
  - 答案
  - 计算机等级考试
id: 258
categories:
  - 考试
date: 2010-03-29 07:09:00
---

<!--more-->本博在今天上午已经发布了[2010年3月计算机二级Access考试的答案](http://chensd.com/2010-03/ncre-2-access-201003-test-answer.html)。这里也有[本次考试的真题](http://www.exam8.com/computer/djks/dj2/Access/zhenti/201003/977199.html)。

试题中的部分题目是可以运行的，同学们下载并试运行**[真题的示例运行程序](../wp-content/upfile/2010/03/NCRE-2-Access-201003-Test-APP.7z)**。

解析如下：

2010年3月二级Access考试答案解析

选择题：

1、A。官方教材P39页．对分查找即二分法查找，二分法查找只能适用于**顺序存储的有序表**；

2、D。算法的时间复杂度主要是基本运算次数。

3、B．操作系统才是系统软件。

4、A。

5、C。**DFD是结构化分析的工具**，结构化分析是需求分析的一种方法。

6、B。详细设计属于SLC中开发阶段的第一步骤，即设计。

7、A。数据定义语言DDL的目的是进行模式定义和物理数据存取的构建。

8、D。一个学生的信息，就是一个元组，即一行或者一条记录。

9、C。官方公共基础教材P127页。**E-R图是概念模式**，在第二阶段概念设计阶段构造。

10、A。选择是行上的操作。

11、D。一方面，表不以独立文件的方式存在，但在表对象中，以不同的单位来进行区别，同时，又通过表之间的关系来构建联系。

12、C。字段名称的正确叫法应该是“**字段标题**”，它主要用于表格的显示。

13、C。系统自动设置为“**有（无重复）索引**”。

14、C。可以输入任意一个字符或者空格，字符可以是字母、数字、标点、加减号等。

15、A

16、D

17、C。没有“密码”这个属性，但是，可以先设置输入掩码，再在输入掩码中填入“密码”二字来完成这个效果（输入字符，显示为*）。

18、D。不能使用等号，只能使用like。含有“网络”二字，可以在首位，可以在中间，也可以在末尾，所以应该是“*网络*”。

19、B

20、D

21、A。只能检查出语法错误，但逻辑错误是不能检查的。例如，当输入了if和then，但如果没有end if，则会提示错误，但如果本应该是在i&gt;10时运行循环体，但如果用了do until i &gt; 10 …Loop，则循环体不会按要求运行。

22、C

23、D。窗体的RecordSource属于是设置窗体数据来源，而“Select * from 雇员”，则是选择该表中的所有记录。

24、D。报表在设计中，标签、图形以及文本框都可以辅导数据或者文字、图片的输入，但选项组控件在设计过程中无法改变其值。

25、B。

26、C。

27、D。

28、需要在千分位进行四舍五入操作，则最后结果肯定是精确到百分位的。而Int只能取整，无法取小数部分，因此，必须对转换对象进行一个先乘以一百，再除以一百的操作。而如果想在千分位进行四舍五入，又必须对于千分位上进行加5的操作。这样，千分位上为4和4以下的，百分位不变，而千分位上5及5以上的，百分位将被加1。

29、B。A(2 to 5, 5)第一个元素为A(2,0)，最后一个元素是A(5,5)，第一维上有2~5四种变化，而第二维上有0~5六种变化，因素元素数为4×6，为24个。

30、A。对于步长为负数且循环变量的初值又比终值小的循环，会直接退出。

31、对于外层的i循环，因为其循环体第1句就是将x置0，所以只用考虑其最后一次循环，最后一次后循环时，i的值为19。此时，里面循环j的初值为19，终值为20，步长为3，则其循环体只运行一次，即x的值只加了一个1。.因此，答案为1

32、do loop while循环是为了控制输入。而直接输出是在Debug.Print y，即if then这个选择中，此题的关键在于读懂if (y Mod 10) + Int(y / 10) = 10这个条件，y mod 10是取y的个位上的数。而Int (y / 10)则是相当于取y的十位上的数，满足这个条件的二位数的y值有。19、28、37、46、55、64、73、82、91，且只能为正数。因此，答案为37 55 64 28 19。

33、此题在于考查对传值和传址的理解。传值为ByVal，传址为ByRef，默认如果不指定则为传址。对于传值，子过程中值的变化不会影响调用它的这个过程，而传址则不然。（亦可用实参形参的概念进行理解）。

34、此题在于理解**DateDiff**，这也是个比较偏的考点。DateDiff有三个参数，第一个为差距的计算单位，第二个为时间起始点，第二个为时间终止点。ww指单位为周，从2009年12月25日到2010年1月5日其中有两周。对于此题，可参考[这里](http://office.microsoft.com/zh-cn/access/HA012288112052.aspx)。详细解析，请点[这里](http://chensd.com/2010-03/vba-datediff.html)。

35、对年龄字段加1，需要使用update的SQL语句，其中格式正确的只有B。

1、对于队列来讲，是先进先出。

2、同2008年4月考试第3题不同的是，这次头指针在尾指针之后，因为是循环队列，所以应该是从45到50，再从1到10构成了这个队列。

3、本题为一二叉树遍历题，LRD的结果为：EDBGHFCA

4、软件=程序+数据+相关文档

5、选课表一方面要连接学生基本信息表，另外一方面还需要连接课程表，所以应该填入课程表中的课号字段。

6、选项组控件中的文字显示，是利用标签控件来实现的，题中的Frame1对应的标签控件名称为Label1，要将这个选项组中显示的“Frame1”，则需要修改Label1的标题Caption属性。答案为：Label1.Caption = “性别”。

7、**要使焦点移到指定的控件，需要使用GoToControl**，而不是网上流传的SetFocus，因为宏操作中根本就没有叫SetFocus的操作。具体可以参考Microsoft Office Online的[相关文档](http://office.microsoft.com/zh-cn/access/HA012262182052.aspx)。

8、在向导中，最多可设置4个分组字段。

9、KeyPress事件是当键盘按下某个键后的所执行的事件，其参数KeyAscii值为按下键所对应的ASCII值，Chr(KeyAscii(i))可以将相应的数值转换成字符，而Ucase是将小写字符转换成大写，而Lcase是将小写转换成大写。另外，ASCII值48~57是数字0~9，65~90是字母A到Z，97~122是字母a到z。因此，该题的答案应该是456aBc。可参考[ASCII码表](http://zh.wikipedia.org/zh-cn/ASCII)。

10、经过第一个for循环，a(i)中a(1) 到a(10)存的分别是1到10的平方。第二个循环后，p(i)中的p(1)存有a(1)的值，p(2)中存的是a(4)的值， p(3)中存的是a(9)的值，经过最后一个循环之后，K的值应该为201

11、题目要求在显示出最小的五个可以同时被5和7除后余1的整数。Do loop until Ncount = 5循环进行整体控制，n = n + 1保证是最小的五个正整数。而if控制的两个语句，一个是打印，一个是对找出的数进行计数。因此，if的条件必定是满足要求的一条语句，要满足这个条件，必须分两方面，一是i mod 5 = 1，二是i mod 7 = 1，要同时满足，则可用and进行连接，答案为：(i mod 5 = 1) and (i mod 7 = 1)

12、本题中，b的目的是为了控制打开debug.print i，而如果想要其不打开这个值，必须歙使得期if后的条件为假，为假的办法就是使b为false，因此，在第【12】空就应填false。k是do while循环的递增变量，因此需要对其进行递增，即k =  k + 1。

13、本题要求对所有的行进行操作，即要从第一行到最后一行，控制的办法就是查看数据集的EOF值，如果为真就到了最后一行。而为了使while循环的循环体对每一行进行操作，就必须使其条件在最后一行时为假，因此使用Not rs.EOF。难点的Not已经由题目给出了。而对数据记进行操作之后，一定要使用Update进行更新，再才能继续下一行的操作。

## 连接

<div>

*   2008年3月和9月试卷下载：[http://chensd.com/2010-03/ncre-2-access-2008-test-papers.html](http://chensd.com/2010-03/ncre-2-access-2008-test-papers.html)
*   2009年3月的试卷下载：[http://chensd.com/2010-03/ncre-2-access-200903-test-papers.html](http://chensd.com/2010-03/ncre-2-access-200903-test-papers.html)
*   2009年9月的试卷下载：[http://chensd.com/2010-03/ncre-2-access-200909-test-papers.html](http://chensd.com/2010-03/ncre-2-access-200909-test-papers.html)
*   2010年3月的试卷（word版）下载：[http://chensd.com/2010-09/ncre-2-access-201003-doc.html](http://chensd.com/2010-09/ncre-2-access-201003-doc.html)
*   2010年3月公共基础题目答案与分析：[http://chensd.com/2010-03/ncre-2-201003-jichu.html](http://chensd.com/2010-03/ncre-2-201003-jichu.html)
*   2010年3月笔试题目答案分析：[http://chensd.com/2010-03/ncre-2-access-201003-answer-analyse.html](http://chensd.com/2010-03/ncre-2-access-201003-answer-analyse.html)
</div>