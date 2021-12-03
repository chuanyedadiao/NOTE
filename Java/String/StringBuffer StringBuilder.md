# StringBuffer StringBuilder

面试题：

String、StringBuffer、StringBuilder三者的异同？

answer：

String：不可变的字符序列 底层用char[]存储

StringBuffer：可变的字符序列；线程安全的，效率低 底层用char[]存储

StringBuilder：可变的字符序列；线程不安全，效率高 底层用char[]存储





StringBuffer

扩容问题：如果添加的数组底层数组盛不下了，就需要扩容底层的数组

​			默认情况下，扩容为原来容量的2倍+2，同时将原来数组中的元素复制到新的数组中



## StringBuffer中常用方法

StringBuffer append : 用于字符串拼接

StringBuffer delete : 删除指定位置的内容

StringBuffer replace : 把[start,end]位置替换为str

StringBuffer insert : 在指定位置插入xxx

StringBuffer reverse : 把当前字符序列逆转



## String、StringBuffer、StringBuilder 效率

StringBuilder > StringBuffer > String
