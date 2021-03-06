# 逻辑表达式（YOJ 1592）
逻辑计算，是针对True和False两个值，做and、or、not等各类逻辑操作。下面请你帮忙写一个逻辑计算器，完成逻辑运算并输出结果。 
## 输入格式
第1行，一个整数n，表示一共有n个需要计算的逻辑表达式。 n <= 10<br>
接下来n行，每行一个表达式，具体参见样例以及说明。<br>
## 输出格式
n行，每行一个整数0或者1，为表达式计算的结果。 

## 输入样例
2<br>
1&1|0<br>
1&0|0<br>

## 输出样例
1<br>
0

## 说明：
True和False分别用1和0来表示，and、or、not分别用'&','|','!'来表示<br>
运算符优先级为'!'>'&'>'|'<br>
运算符和操作数之间可能有空格，也可能没有。<br>
样例输入为一个逻辑表达式，输出为其计算结果。 <br>

## 示例程序（选自同学们提交的程序）
* [logic_2134.cpp](https://github.com/fanju1984/introduction-to-programming/blob/master/introduction-to-programming/course-project/2018/problem/logic_2134.cpp)
* [logic_2168.cpp](https://github.com/fanju1984/introduction-to-programming/blob/master/introduction-to-programming/course-project/2018/problem/logic_2168.cpp)
# 比较表达式 （YOJ 1597）
小明最近拿到老师交给他的几组股票数据，但是数据中有很多比较任务，因此需要你写一个比较器帮忙比较大小。
## 输入格式
第一行一个数字n，表示这条记录包含的字段数目<br>
下面n行每行依次输入字段名，字段类型，字段的值，中间以冒号分割<br>
紧接着一个数字m，表示要比较的表达式数目，<br>
下面m行每行为一个比较表达式，分为三部分，第一部分为一个字段名，第二部分为一个运算符，第三部分为一个值，三部分中间以空格分隔。<br>
## 输出格式
m行，比较表达式的运算结果，1表示True，0表示False，如果输入的表达式中字段名有误，则输出-1
## 输入样例
3<br>
OPEN:INT:5<br>
CLOSE:DOUBLE:7.0<br>
CODE:STRING:asYouSaid<br>
5<br>
OPEN > 5<br>
Open = 5<br>
OPEN < 5<br>
CLOSE > 1<br>
CODE = asYouSaid<br>
## 输出样例
0<br>
1<br>
0<br>
1<br>
1<br>
## 特殊提示
1. 向程序中输入字段时字段名的大小写可能会发生变化。<br>
2. 1<=n<=10，字段名长度不超过10，数据类型限定为int,double,string（大小写可能发生变化），分别代表整型、浮点型和字符串，比较运算符限定为 >,=,< 三个<br>

## 示例程序（同学们提交的程序+原程序代码样例）
* [cmp_2077.cpp](https://github.com/fanju1984/introduction-to-programming/blob/master/introduction-to-programming/course-project/2018/problem/cmp_2077.cpp)
* [cmp_2194.cpp](https://github.com/fanju1984/introduction-to-programming/blob/master/introduction-to-programming/course-project/2018/problem/cmp_2194.cpp)
* [cmp_ref.cpp](https://github.com/fanju1984/introduction-to-programming/blob/master/introduction-to-programming/course-project/2018/problem/cmp_ref.cpp)
