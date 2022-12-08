# 编程基础检查表

本文是基于《自学是门手艺》的编程基础检查表，不涉及具体内容，看到下面的内容，大脑中能立即反应出来是什么，能快速想到基本使用场景就表示初步掌握。

## 1.入口

### 1.1.布尔值

* Ture
* False



### 1.2.逻辑操作符

| 比较操作符 | 意义     | 示例             | 布尔值  |
| ---------- | -------- | ---------------- | ------- |
| `==`       | 等于     | `1 == 2`         | `False` |
| `!=`       | 不等于   | `1 != 2`         | `True`  |
| `>`        | 大于     | `1 > 2`          | `False` |
| `>=`       | 大于等于 | `1 >= 1`         | `True`  |
| `<`        | 小于     | `1 < 2`          | `True`  |
| `<=`       | 小于等于 | `1 <= 2`         | `True`  |
| `in`       | 属于     | `'a' in 'basic'` | `True`  |



### 1.3.布尔运算操作符

and, or, not

| and   | Ture  | False |
| ----- | ----- | ----- |
| True  | True  | False |
| False | False | False |

| or    | Ture | False |
| ----- | ---- | ----- |
| True  | True | True  |
| False | True | False |

| not  | Ture  | False |
| ---- | ----- | ----- |
|      | False | True  |
|      |       |       |



### 1.4.流程控制

#### 判断（分支）

* if/else

#### 循环

* for/in



### 1.5.函数

* 函数名
* 参数
* 返回值
* 调用
  * 被调用的函数，也可以被理解为**子程序**（Sub-Program）—— 主程序执行到函数调用时，就开始执行实现函数的那些代码，而后再返回主程序……（Mumu Wu）



### 1.6.操作符

* `%`，`+`，`-`，`*`，`/`，`//`，`**`

  * `//`:余

  * `**`:幂

* 操作与赋值连用的顺序
  * `x = x + 1` 



### 1.7.其他概念

* 赋值
* 变量
* 常量
* 循环嵌套
* 遍历
* 语句
* 语句块
  * 如果有行首空白存在，那么，Python 将认为这一行与其他邻近有着相同行首空白的语句同属于一个**语句块**
* 注释
  * `#`
  



## 2.值及其相应的运算


### 2.2.值的类型

* 布尔值
* 数字
* 整数
* 浮点数
* 复数(Complex Numbers)
  * 复数由实部（real）和虚部（imag）构成，在 Python 中，复数的虚部以`j`或者`J`作为后缀
* 字符串
* type()

### 2.3.操作符

#### 2.3.1.数值操作符

`+`、`-`、`*`、`/`、`//`、`%`、`**`

#### 2.3.2.布尔值操作符

`与`、`或`、`非`：`and`、`or`、`not`

#### 2.3.3.逻辑操作符

`<`（小于）、`<=`（小于等于）、`>`（大于）、`>=`（大于等于）、`!=`（不等于）、`==`（等于）

#### 2.3.4.字符串操作符

* 拼接：`+` 和 `' '`（后者是空格）
* 拷贝：`*`
  * 'Python' * 3  #3次Python
* 逻辑运算：`in`、`not in`；以及，`<`、`<=`、`>`、`>=`、`!=`、`==`

#### 2.3.5.列表的操作符

* 拼接：`+` 和 `' '`（后者是空格）
* 拷贝：`*`
* 逻辑运算：`in`、`not in`；以及，`<`、`<=`、`>`、`>=`、`!=`、`==`

#### 2.3.6.Python内建函数

|                                                              | Python                                                       | Built-in                                                     | Functions                                                    | )                                                            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [abs()](https://docs.python.org/3/library/functions.html#abs) | [delattr()](https://docs.python.org/3/library/functions.html#delattr) | [hash()](https://docs.python.org/3/library/functions.html#hash) | [memoryview()](https://docs.python.org/3/library/functions.html#func-memoryview) | [set()](https://docs.python.org/3/library/functions.html#func-set) |
| [all()](https://docs.python.org/3/library/functions.html#all) | [dict()](https://docs.python.org/3/library/functions.html#func-dict) | [help()](https://docs.python.org/3/library/functions.html#help) | [min()](https://docs.python.org/3/library/functions.html#min) | [setattr()](https://docs.python.org/3/library/functions.html#setattr) |
| [any()](https://docs.python.org/3/library/functions.html#any) | [dir()](https://docs.python.org/3/library/functions.html#dir) | [hex()](https://docs.python.org/3/library/functions.html#hex) | [next()](https://docs.python.org/3/library/functions.html#next) | [slice()](https://docs.python.org/3/library/functions.html#slice) |
| [ascii()](https://docs.python.org/3/library/functions.html#ascii) | [divmod()](https://docs.python.org/3/library/functions.html#divmod) | [id()](https://docs.python.org/3/library/functions.html#id)  | [object()](https://docs.python.org/3/library/functions.html#object) | [sorted()](https://docs.python.org/3/library/functions.html#sorted) |
| [bin()](https://docs.python.org/3/library/functions.html#bin) | [enumerate()](https://docs.python.org/3/library/functions.html#enumerate) | [input()](https://docs.python.org/3/library/functions.html#input) | [oct()](https://docs.python.org/3/library/functions.html#oct) | [staticmethod()](https://docs.python.org/3/library/functions.html#staticmethod) |
| [bool()](https://docs.python.org/3/library/functions.html#bool) | [eval()](https://docs.python.org/3/library/functions.html#eval) | [int()](https://docs.python.org/3/library/functions.html#int) | [open()](https://docs.python.org/3/library/functions.html#open) | [str()](https://docs.python.org/3/library/functions.html#func-str) |
| [breakpoint()](https://docs.python.org/3/library/functions.html#breakpoint) | [exec()](https://docs.python.org/3/library/functions.html#exec) | [isinstance()](https://docs.python.org/3/library/functions.html#isinstance) | [ord()](https://docs.python.org/3/library/functions.html#ord) | [sum()](https://docs.python.org/3/library/functions.html#sum) |
| [bytearray()](https://docs.python.org/3/library/functions.html#func-bytearray) | [filter()](https://docs.python.org/3/library/functions.html#filter) | [issubclass()](https://docs.python.org/3/library/functions.html#issubclass) | [pow()](https://docs.python.org/3/library/functions.html#pow) | [super()](https://docs.python.org/3/library/functions.html#super) |
| [bytes()](https://docs.python.org/3/library/functions.html#func-bytes) | [float()](https://docs.python.org/3/library/functions.html#float) | [iter()](https://docs.python.org/3/library/functions.html#iter) | [print()](https://docs.python.org/3/library/functions.html#print) | [tuple()](https://docs.python.org/3/library/functions.html#func-tuple) |
| [callable()](https://docs.python.org/3/library/functions.html#callable) | [format()](https://docs.python.org/3/library/functions.html#format) | [len()](https://docs.python.org/3/library/functions.html#len) | [property()](https://docs.python.org/3/library/functions.html#property) | [type()](https://docs.python.org/3/library/functions.html#type) |
| [chr()](https://docs.python.org/3/library/functions.html#chr) | [frozenset()](https://docs.python.org/3/library/functions.html#func-frozenset) | [list()](https://docs.python.org/3/library/functions.html#func-list) | [range()](https://docs.python.org/3/library/functions.html#func-range) | [vars()](https://docs.python.org/3/library/functions.html#vars) |
| [classmethod()](https://docs.python.org/3/library/functions.html#classmethod) | [getattr()](https://docs.python.org/3/library/functions.html#getattr) | [locals()](https://docs.python.org/3/library/functions.html#locals) | [repr()](https://docs.python.org/3/library/functions.html#repr) | [zip()](https://docs.python.org/3/library/functions.html#zip) |
| [compile()](https://docs.python.org/3/library/functions.html#compile) | [globals()](https://docs.python.org/3/library/functions.html#globals) | [map()](https://docs.python.org/3/library/functions.html#map) | [reversed()](https://docs.python.org/3/library/functions.html#reversed) | [__import__()](https://docs.python.org/3/library/functions.html#__import__) |
| [complex()](https://docs.python.org/3/library/functions.html#complex) | [hasattr()](https://docs.python.org/3/library/functions.html#hasattr) | [max()](https://docs.python.org/3/library/functions.html#max) | [round()](https://docs.python.org/3/library/functions.html#round) |                                                              |

#### 2.3.7.标准库

* math
  * math.sin()
* 什么是类（Class）
  * 类的函数，比如float这个类
    * float.as_integer_ratio()

#### 2.3.8.值得类型的补充

`range()`（等差数列）`tuple`（元组）、`set`（集合）、`dictionary`（字典），再比如 `Date Type`（日期）等等。



## 3.流程控制

### 3.1.if语句

* if
* elif
* else

### 3.2.for循环

* for in

#### 3.2.1.range()函数

**range**(_stop_)

**range**(_start, stop[, step]_)

#### 3.2.2.Continue、Break和Pass

* Continue
  * 跳出本次循环
* Break
  * 跳出循环
* Pass
  * 什么都不干，占位

### 3.3.while循环