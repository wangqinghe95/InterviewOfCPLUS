# 右值引用
+ 为了实现不必要的copy消耗，是C++的一个新的引用类型

+ 左值：可以放在等号左边，比如变量，就是一个左值，可以放在等号左边被赋值
+ 右值：只能出现在等号右边，比如临时对象，函数返回值

但是如果我们需要把右值放到
