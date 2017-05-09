# 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
- new repository 
- import repository(导入仓库)
- new gist（新的一个代码片段,新要点）
- new organization

# 如何能将仓库中的html文件直接解析成页面？
- 创建新文件，在设置中找source 选第一个

# 如何删除仓库
- 在仓库页面的设置中找danger区中delete

# Bash是什么操作系统的命令
- Linux

# Pwd是什么命令
- print working directory

# Cd是什么命令
- 改变目录change directory

# Echo是什么命令
- 在命令行打印一个信息  
  echo 'hello'打印hello    echo 'hello' > a.txt通过管道将hello传入a.txt文件中，如果没有a.txt文件则新建
- ----cp a.txt b.txt将文件a赋值
- ----ls..移到上一级目录
- ----mv b.txt ../b.txt将文件b移到上一级
- ----mv a.txt c.txt 完成文件的重命名
- ----rm c.txt 删除文件
- ----clear清屏（Ctrl+L）

# 显示当前配置
- git config –list

# 配置git用户名的命令
- git config --global user.name"刘薇"

# 配置邮箱的命令
- git config --global user.email1013488645@qq.com

# 命令行换行方式
反斜杠  \br也行

# 命令行终结方式
- ctrl +c 
# 使用命令行比GUI方式有何优势

- *很多工具没有GUI，只有命令行
- *命令行程序的开发比GUI要容易一万倍，命令行一打命令就能用
- *在出错的时候更明显，命令行一般会告诉你错在哪里，可以针对性地做排查诊断，但大部分GUI只会告诉你出错了，甚至有些写得不好的GUI根本无法判断到底有没有出错
- *兼容性和适应性更强
- *可以进行批处理

# 提交到本地仓库时为什么有暂存区
 	- workspace 到仓库中间有个暂存区（index）因为他是托管，中间区域就有commit之前的和之后的

# 新建代码仓库的命令
- git init（在当前目录下）
# git clone [url] 这个命令的作用是
1. 远程的仓库下载到当前的pwd下，克隆，本地和github 链接
2. 下载一个项目和他的整个代码历史

# 添加指定文件到暂存区的命令
git add [file1] [f2]

# 删除工作区文件，并且将这次删除放入暂存区的命令
git rm [file1] [f2]
 
# 改名文件，并且将这个改名文件放入暂存区的命令
git mv [file-origin] [file-rename]

# 提交暂存区到仓库的命令
git commit -m [message]
# 直接从工作区提交到仓库的命令
git commit -a -m [message提交信息]
# 显示变更信息的命令
git status
# 查看历史信息的命令（命令行的翻页和退出也是这个）
git log

#### j、k（向上）键上下使用—vim中的操作去搜vim的快捷键都是一致的
