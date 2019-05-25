## 1 下载

下载地址：<https://git-for-windows.github.io/> 

## 2 安装

- 双击之后一路Next

  ![img](https://img-blog.csdn.net/20171207211713874?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“next”按钮，进入Select Destination Location界面，可根据自己的需求修改安装路径 

  ![img](https://img-blog.csdn.net/20171207211736584?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“next”按钮，进入Select Componets界面，选择要安装的组件，详情见图。  

  ![img](https://img-blog.csdn.net/20171207211813159?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“next”，进入Select Start Menu Folder界面，设置开始菜单中快捷方式的目录名称,  

  ![img](https://img-blog.csdn.net/20171207211749972?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“Next”选择默认编辑器我选择的“Vim” 

  ![img](https://img-blog.csdn.net/20171207211832260?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“next”，进入Adjusting your PATH environment界面，设置环境变量 ：选择使用什么样的命令行工具使用git，我选择了git bash和windows命令行。 

  ![img](https://img-blog.csdn.net/20171207212432048?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“Next”选择传输后台使用OpenSSL 

  ![img](https://img-blog.csdn.net/20171207212628171?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“next”按钮进入Configuring the line ending conversions界面，选择换行格式，windows上跨平台支持，unix以及非跨平台支持。 

  ![img](https://img-blog.csdn.net/20171207213058983?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“next”按钮进入配置终端模拟器（Configuring the terminal emulator to use with Git Bash）界面，默认设置 

  ![img](https://img-blog.csdn.net/20171207213116209?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“next”按钮进入额外的配置选项（Configuring extra options），默认设置。允许系统缓存，允许信任证书管理 

  ![img](https://img-blog.csdn.net/20171207213136659?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 点击“Install”开始安装。 

  ![img](https://img-blog.csdn.net/20171207214224935?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 安装完成 

  ![img](https://img-blog.csdn.net/20171207214318878?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

- 此时我们在文件管理器中点击右键就可以看到打开git的菜单  

  ![è¿éåå¾çæè¿°](https://img-blog.csdn.net/20171207214721500?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzI5NTUxOA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 

  ## 3 配置本地信息

  Windows下打开Git Bash ，输入如下：

  git config --global user.name "github账户名"
  git config --global user.email github配置的邮箱

  git config –list 查看配置结果 

  ## 4 Git配置

  ### 4.1 通过Git生成SSH Key

- 输入命令后一路回车：

  $ ssh-keygen -t rsa -C “注册邮箱”

- 文件夹.ssh中即为刚才命令生成的秘钥

  ![1558808388330](C:\Users\1\AppData\Local\Temp\1558808388330.png)

  ### 4.2 添加公钥到github

  ![1558808464733](C:\Users\1\AppData\Local\Temp\1558808464733.png)

  ### 4.3 测试连接

  测试ssh key是否成功，使用命令ssh -T git@github.com，如果出现You’ve successfully authenticated, but GitHub does not provide shell access 。这就表示已成功连上github。如图： 

  ![1558808680435](C:\Users\1\AppData\Local\Temp\1558808680435.png)

  

  