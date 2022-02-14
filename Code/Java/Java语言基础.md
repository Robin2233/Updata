###IDEA界面不能正常输入，光标变粗
+ ####按了 enter+insert 快捷键造成的
> fn+insert切回

+ 含有main方法的类称之为主类，java是严格区分大小写的

| 数据类型  | 内存空间（8位等于1字节） | 取值范围      |
|-------|---------------|-----------|
| byte  | 8位            | -128——127 |
| short | 16位           ||
| int   | 32位           ||
| long  | 64位           ||
> 基本数据类型：数值型（整数型（byte，sgort，int，long），浮点型，有小数部分的数字（floate，double）），字符型，布尔型
+ 默认情况小数都被看做双精度bouble型，若使用单精度floate需要末尾加f，而double可加可不加

```java
floate f=3.23f；//不加f会认为是double变量而报错
double d1=2323.12d；
double d2=1212.12；
```

+ 对于Log型数据，若赋给值大于int最大值或小于int最小值，则需要在数字后面加L或者l，表示该数为长整数

```java
int x;//定义int变量x
int x,y;//定义int变量x，y
int x=110,y=120;//定义x，y变量并赋值
        
long num=2147483650L;
```
###字符类型
> char型
+ 用于储存单个字符，占用16位（两个字节），单引号表示，而双引号表示字符串
```java
char x='a';
char x=97;//由于a在uniccod排97，等同于
(char)x;//转换值为97
(int)97;
```
>转义字符
+ 特殊字符变量，以
```java
                           
```
```java

```
