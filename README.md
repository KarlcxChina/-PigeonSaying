# PigeonSaying
无聊写的小编码东西，类似于“兽音译者”“与佛论道”
#### 码率极低！
它的基本组成结构为汉字“咕”“鸽”以及英文符号“!”“?”以及“\~”
运行原理是将文本通过易语言转化为字节集并进行Base64编码，将结尾的=替换为“鸽”并加上“?!”,然后将Base64中用到的字符以ABC...abc...123...+/的顺序编号，并将10进制编号转换为8进制数，其中64转化为00。然后以每一个数字对应一组文本的方式组成密文。
数字文本对应如下：
0 -> “咕!!”
1 -> “咕!”
2 ->  “咕?”
3 -> “咕~”
4 -> “咕咕!!”
5 -> “咕咕!”
6 -> “咕咕?”
7 -> “咕咕~”
