1.首先：安装完成后再桌面右击点击git bash然后输入两条指令
2. git config --global user.name "Your Name"
 git config --global user.email "email@example.com"
3.再某个文件目录下创建文件夹例如：learning
4.打开cmd    cd learning进入此目录
5.在此写一个文件夹写一个readme.txt文件
6.创建版本库 git init
7.文件添加到版本库 git add readme.txt
8.git commit -m "wrote a readme file" ------m "描述文件的内容"
9.文档修改了之后，首先你要查看 git status看文件的状态
10.git diff 可以看文件内的内容
11.git add readme.txt文件
12.再此查看 git status看文件的状态
13.在此提交 git commit -m "描述文件"