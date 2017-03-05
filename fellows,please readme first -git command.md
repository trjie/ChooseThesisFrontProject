1. 安装git工具
2. 打开git bash
3. 使用 "cd" 命令跳转到一个自己想保存文件的目录
4. 使用 "git clone 项目Url"  克隆项目到本地要保存的目录里

**例：**

**git clone https://github.com/HurricanGod/ChooseThesisFrontProject**



**提交新内容**

- git bash命令行下使用cd命令进入项目文件夹
- git status (查看库的状态，文件修改后)
- git add 文件名(把文件添加到本地仓库，要提交最新修改的内容到自己的远程仓库必须先执行这条命令。偷懒方法：**进入项目文件，运行"git add ./"命令**，即把当前目录下的所有文件添加到本地仓库进行管理)
- git pull  从远程仓库获取最新的数据（即把网页上的项目下载到本地）并与本地仓库里的内容合并（**git add前最好先git pull一下**保证项目内容是最新的）
- git commit  -m '备注（可以任意内容）' (将工作区中被git跟踪的文件的最新修改提交到暂存区) 
- git push 将暂存区的修改提交到远程仓库，即网页上仓库

**学会以上5条命令就可以简单操作git**

提交最新版本项目操作步骤：

1. **git status **（可以在后续步骤多次使用）
2. **git pull**
3. **git add  ./**
4. **git commit  -m '备注（可以任意内容）'**
5. **git push**