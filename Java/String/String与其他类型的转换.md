# String与其他类型的转换



## part1:String和基本数据类型、包装类之间的转换

* String-->基本数据类型、包装类之间的转换
  * String --> 基本数据类型，包装类
  * 解决方法：调用包装类的静态方法， parseXXX(str)
    * int num = Integer.parseInt(str1)
* 基本数据类型、包装类-->String之间的转换
  * 解决方法：调用String重载的valueOf(XXX)
  * String s = String.valueOf(num)



## part2:String与char型数组之间的转换

* string -->char[]
  * str.toCharArray()
* char[] --> string
  * 利用构造器  new String(arr)



## part3:String与byte型数组之间的转换

* string -->byte[]
  * str.getBytes()
* byte[] --> string
  * 利用构造器  new String(bytes)

