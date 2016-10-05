记录一下啊，~是当前用户的根目录，不同操作系统里是不一样的，比如屌丝win的是C/user/Administrator，最好pwd一下看看一打开bash的时候自己在哪里。。然后就是cd 命令，可以写绝对路径/相对路径，相对路径就是相对当前目录，绝对路径就是/开头的。

然后我们来复习由头到尾的git命令
1.安装git
2.pwd
3.cd /E
4.mkdir learngit
5.init git
6.touch readme.txt
7.编写第一版的readme.txt，放在learngit的目录下
8.git add readme.txt
9.git commit -m "提交第一版的readme.txt"
10.修改第一版的readme.txt并保存
11.git status
11.git diff readme.txt
12.git add readme.txt
13.git status
14.git commit -m "提交第二版的readme.txt"