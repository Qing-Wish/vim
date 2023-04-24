# vim 笔记

**Qing-Wish** 

<u>2023/4/21</u>

> 以下笔记来自于YouTube视频[vim入门教程（第1讲）](https://www.youtube.com/watch?v=L8aOnqxMPis)

## 命令模式下的进入退出等

`:syntax on` 可以实现代码高亮
`:set number`可以实现显示行号
`:w`是保存
`:q`是退出
`:wq`是退出且保存；后面跟文件名的话，该文本会被命名为这个名字。例如`:wq code.c`就是退出且该文本被命名为code.c
`:q!`是不保存退出，会丢弃本次所做的全部修改

> 以下笔记来自于YouTube视频[vim入门教程（第2讲）](https://www.youtube.com/watch?v=gZ8HBGwfLAo&t=47s)

## 命令模式下如何移动光标，查找复制等

命令模式下`j`下`k`上`h`左`l`右；`数字+j`向下跳多少行，`数字+k`向上跳多少行
`w`快速划到下一个单词
`b`快速划到上一个单词
`ctrl+f`翻到下一页
`ctrl+b`翻到上一页
`数字+gg`是跳转到数字那一行
`cc`是<mark>剪切</mark>掉当前所在的那一行；`c2c`是剪切掉光标所在的那2行；`u`是恢复上一步（因为u=undo）；`p`是粘贴；`yy`是复制当前这一行；`dd`是删除当前行
`/node`是查找文本中的所有node；`n`是跳转下一个node；`shift+n`是跳转到上一个node

> 以下笔记来自于YouTube视频[vim入门教程（第3讲）](https://www.youtube.com/watch?v=_HWD6RxnG3M) 

`v`进入visual模式，可以选中长段光标

