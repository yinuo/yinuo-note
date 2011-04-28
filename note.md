#April 24th
##做版本
1. mkdir note.md
2. git init
3. git add note.md
4. git ci "the version"
5. git push

##ctags
1. sudo apt-get install exuberant-ctags
2. ctags + .c文件
3. ctrl+] 跳到调用
4. ctrl+o 返回

##remove a repository
   dashboard -> projectname -> admin ->delete

##gdb
1. gcc sum.c -g -0 sum
   -g 为调试信息,sum为起的名字
2. gdb sum
1> help命令

2> list

###
1. 列出源文件，列出十行。缩写为l
2. 在gdb中直接打enter,执行上次执行的命令
3. l加数字，比如l+2是从第二行向下开始的十行
4. l加函数名，比如l main 列出main函数上下的十行。

