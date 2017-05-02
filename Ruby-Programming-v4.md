# Ruby基础教程

## 1.1

```Ruby
print("Hello, Ruby.\n")
```

## 1.2.2

```Ruby
print("Hello, RUBY.\n")
```

## 1.3.1 换行符

```Ruby
print("Hello,\nRuby\n!\n")

print("Hello,
Ruby
!
") # 不使用换行符会降低程序的可读性

## 转义"
print("Hello, \"Ruby\".\n")

## 转义\
print("Hello \\ Ruby!")
```

## 1.3.2 ''与""

```Ruby
print('Hello, \nRuby\n!\n')

print('Hello, \\ \'Ruby\'.')
```

## 1.4

```Ruby
=begin
Ruby在调用方法时可以省略()
=end
print "Hello, Ruby.\n"

## 连续输出多字符串
print "Hello, ", "Ruby", ".", "\n"
```

## 1.5 puts方法与print方法稍有区别，puts方法在输出结果的末尾一定会输出换行符


puts "Hello, Ruby."
## 参数为两个字符串的时候，各字符串末尾都会加上换行符
puts "Hello, ", "Ruby!"

## 1.6 p方法，数值和字符串结果会以不同的形式展示
puts "100"  #=> 100
puts 100    #=> 100
p "100"     #=> "100"
p 100       #=> 100

## p方法，换行符(\n)、制表符(\t)等特殊字符不会转义
puts "Hello, \n\tRuby."
p "hello, \n\tRuby."

## 1.7 中文输出
print "话说某个朝代，后宫嫔妃甚多，\n"
print "其中有一宫女，出身并不十分高贵，却蒙圣恩宠爱。\n"

## 1.8 数值表示与计算
## 1.8.3 数学相关的函数
=begin
使用数学函数时，必须在函数前加上Math.标识
不想在函数前加Math.时，则需要include Math这段代码
=end
puts Math.sin(3.1415)
puts Math.sqrt(10000)

## 1.9 变量
=begin
可以将其理解为给对象贴上的标签
变量名 = 对象 # 这个过程被称为赋值
=end

## 求长方体表面积
x = 10
y = 20
z = 30
area = (x*y + y*z + z*x) * 2
volume = x * y * z
print "表面积=", area, "\n"
print "体积=", volume, "\n"

# 不使用变量
print "表面积=", (10*20 + 20*30 + 30*10) * 2, "\n"
print "体积=", 10*20*30, "\n"

## 1.10 注释
=begin
单行注释用 #
多行注释用在行的开头输入=begin和=end括起来
=end

## 1.11 控制语句
=begin
顺序控制：按照程序编写的顺序执行，从头到尾
条件控制：若条件成立，执行A，否则执行B
循环控制：在某条件成立之前，反复执行
异常控制：发生异常时执行
=end

## 1.12 条件判断

## 第3章 创建命令

###
