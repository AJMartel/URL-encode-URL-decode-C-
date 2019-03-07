# URL-encode-URL-decode-C-

URL encode and URL decode C language implementation URL encoding does the following:

The characters "a"-"z","A"-"Z","0"-"9",".","-","*", and "_" are not encoded, maintaining the original value;

The space " " is converted to the plus sign "+".

Each of the other bytes is represented as a string of 3 characters in the "%xy" format, encoded as UTF-8.




URL encode 与 URL decode 的C语言实现
URL编码做了如下操作：

字符"a"-"z"，"A"-"Z"，"0"-"9"，"."，"-"，"*"，和"_" 都不被编码，维持原值；

空格" "被转换为加号"+"。

其他每个字节都被表示成"%xy"格式的由3个字符组成的字符串，编码为UTF-8。
