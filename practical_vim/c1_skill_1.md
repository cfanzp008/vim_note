# 《Vim实用技巧（第2版）》技巧1-认识.命令
## 1. 什么是.命令？
- 命令(点命令) 可以重复上次的修改
- 命令是Vim中的瑞士军刀
- 点命令是一个微型的宏

## 2. 点命令说的重复的“修改”指的是什么？
- x 删除一个字符
- dd 删掉一行
- \>G 缩进

## 3. 举例
- 输入daw删除1个单词后，可以按键盘中的.来重复删除后面一个单词(. == daw) 。

## 4. 点命令有什么优点？
- 点命令让可以重复的修改变得简单快捷，大大提高了输入效率。

## 5. 点命令有什么优点？
- 哪些情况需要使用点命令，这个问题还需要平时练习中多思考总结。
- 如果你发现自己要在几个地方同样的小修改，就可以尝试构造你的修改，让它能够被 点命令执行。
