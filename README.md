# C语言程序设计（专升本）

[![](https://badgen.net/badge/icon/Website?icon=chrome&label)](https://feeds.pub/cn-独立) 
[![](https://badgen.net/badge/icon/Telegram?icon=telegram&label)](https://t.me/DateTricker)
[![](https://badgen.net/badge/icon/Blog?icon=chrome&label)](https://blog.t9t.io/cn-独立博客-2019-10-29/)

## 赞助商

[琚致远](https://github.com/juzhiyuan) | [字节库](https://bytebase.com/) | [马道](https://madao.me/) | [第二状态](https://bit.ly/3gfWwps)

[成为赞助商](https://github.com/sponsors/timqian)

## 项目目录

- [正文](#正文)

# 正文

## 关键字
	
	包括数据类型关键字（12个）、控制语句关键字（12个）、存储类型关键字（4个）、其他类型关键字（4个）

### 数据类型关键字（12个）

int 声明整型变量或函数

short 声明短整型变量或函数

long 声明长整型变量或函数

float 声明单精度浮点型变量或函数

double 声明双精度浮点型变量或函数

char 声明字符型变量或函数

enum 声明枚举型变量或函数

signed 声明有符号型变量或函数

unsigned 声明无符号型变量或函数

struct 声明结构体型变量或函数

union 声明共用体（联合）型变量或函数

void 声明无类型（无参数或无返回值）指针变量或函数

### 控制语句关键字（12个）

#### 循环语句关键字（5个）

for | for循环

do | do-whlie循环

while | while循环/do-while循环

break | 跳出当前循环

continue | 结束当前循环并开始下一轮循环

#### 条件语句关键字（3个）

if | if语句/if-else语句

else | if-else语句

goto | 无条件跳转语句

#### 开关语句关键字（3个）

switch | switch语句/switch-case语句（开关语句）

case | switch-case语句（开关语句分支）

default | 开关语句其他分支

#### 返回语句关键字（1个）

return | 子程序返回语句（可以带参数或不带参数）

### 存储类型关键字（4个）

auto | 声明自动变量（一般不使用）

extern | 声明变量在其他文件中正声明（或看作引用变量）

register | 声明寄存器变量

static | 声明静态变量

### 其他类型关键字（4个）

const | 声明只读变量

sizeof | 计算数据类型长度

typedef | 用作给数据类型取别名（或其他作用）

volatile | 说明变量在程序运行在可被隐含地改变

## 运算符

	包括算术运算符、赋值运算符、复合赋值运算符、递增递减运算符（单目运算符）

### 算术运算符

加法运算符 +

减法运算符 -

乘法运算符 *

乘法运算符 /

取余(模)运算符 %

### 赋值运算符

赋值运算符 =

### 复合赋值运算符

加法赋值运算符 +=

减法赋值运算符 -=

乘法赋值运算符 *=

除法赋值运算符 /=

取余（模）赋值运算符 %=

### 递增递减运算符（单目运算符）

递增(自增)运算符 ++

递减(自减)运算符 --

## 控制语句

	包括分支（条件判断）语句、循环语句、转向语句

### 分支（条件判断）语句

if语句

switch语句

### 循环语句

while语句

do-while语句

for语句

### 转向语句

brack语句

goto语句

continue语句

return语句

## 数据类型

	包括基本类型、构造类型、其他类型

### 基本类型

整型 int

字符型 char

浮点型（实型）

单精度浮点型 float

双精度浮点型 double

### 构造类型

数组类型 [ ]

结构类型 struct

联合类型 union

枚举类型 enum

### 其他类型

指针类型 *

空类型（无值型）void

## 常量

	包括整型常量、浮点型常量、字符型常量、字符串型常量、符号常量

### 整型常量

250、-100、0

### 浮点型常量

0.25、3.14、-3.44

### 字符型常量

‘a’、‘b’、‘1’

### 字符串型常量

“你好”、“a”、“1c34”

### 符号常量

？#define a 3

## 程序结构

	包括顺序结构、选择结构（分支结构）、循环结构（重复结构）

### 顺序结构

### 选择结构（分支结构）

#### 简单选择结构

if语句

#### 复杂选择结构

嵌套if语句

switch语句

### 循环结构（重复结构）

while循环（后执型结构）

	while循环＝while(表达式){循环体}

do while循环（先执型结构）

	do while循环＝do{循环体}while(表达式)

for循环

	for循环＝for(表达式1；表达式2；表达式3){循环体}

	for循环＝for(变量初值；判定条件；改变变量){循环体}
