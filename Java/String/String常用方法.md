# String常用方法

## part1

* int length() 返回字符串的长度  return value.length
  * 底层数组的长度
* char charAt(int index) 取指定位置上的一个字符 return value[index]
* boolean isEmpty() 判断是否是空字符串 return value.length == 0
* String toLowerCase() 将String中的字符全部转换为小写，原字符串不变，会有一个返回值
* String toUpperCase() 将String中的字符全部转换为大写，原字符串不变，会有一个返回值
* String trim() 去除首位空格
* boolean equals(Object obj) 比较内容是否相同
* boolean equalsIgnoreCase(Object obj) 比较内容是否相同，忽略大小写
* String concat(String str) ：将指定字符串链接到此字符串的结尾 等价于用“+”
* int compareTo(Stirng anotherString) 比较两个字符串的大小
* String substring(int beginIndex)
* String substring(int beginIndex, int endIndex)





## part2

* boolean endsWith(String suffix) 测试此字符串是否以指定的后缀结束
* boolean startsWith(String prefix) 测试此字符串是否以指定的前缀开始
* boolean startsWith(String prefix, int toffset) 测试此字符串从指定索引开始的子字符串是否以指定的前缀开始
* boolean contains(CharSequence s) 当且仅当此字符串包含指定的char值序列时，返回true
* int  indexOf(String str):返回指定字符串str在此字符串中第一次出现处的索引
* inde indexOf(String str,int fromIndex) 返回指定字符串str在此从fromIndex开始字符串中第一次出现处的索引
* int lastIndexOf(String str) 返回指定子字符串str在字符串中最右边出现处的索引
* int lastIndexOf(String str,int fromIndex) 返回指定子字符串在此字符串中最后一次出现处的索引，从指定的索引开始反向搜索



什么情况下 indexOf和lastIndexOf的返回值相同？

	1. 只有一个对应的str
 	2. 没有str存在





## part3

* String replace(char oldChar, char newChar) 更换全部
* String replace(CharSequence target, CharSequence replacement) 更换全部
* String replaceAll(String regex,String replacement) 正则
* String replaceFirst(String regex,String replacement)
* boolean matches(String regex) 是否匹配给定的正则表达式
* String split(String regex) 切片
* String split(String regex,int limit) 切片