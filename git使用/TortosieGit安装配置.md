## 1 先安装并配置好git

## 2 安装TortoiseGit

下载：<https://tortoisegit.org/download/> 

先安装程序包，再安装语言包 

## 3 配置TortoiseGit


- 在空白处点击鼠标右键, 选择 --> TortoiseGit --> Settings, 弹出配置界面(当TortoiseGit安装完成后，鼠标右键点击后，默认出现 TortoiseGit 相关选项)

  ![1558809117866](D:\cloneCode\NOTE\git使用\1558809117866.png)

### 3.1 配置密钥 

#### 3.1.1密钥生成及添加

- 找到安装目录下的puttygen.exe运行

![1558810745476](C:\Users\1\AppData\Local\Temp\1558810745476.png)

![img](https://images2018.cnblogs.com/blog/1090314/201807/1090314-20180715111951451-1345753291.png) 

- 点击Generate,生成的过程中

　　注意：生成时鼠标要不停划过进度条，不然进度条会一直不动！

![img](https://images2018.cnblogs.com/blog/1090314/201807/1090314-20180715112003745-2010648467.png) 

- 先点击Save private key把私有的密钥存起来，记住存储的位置,后面会用到

　　  把生成出来的public Key复制粘贴到Github上面，配置SSH key

![img](https://images2018.cnblogs.com/blog/1090314/201807/1090314-20180715112132941-1633602668.png) 

#### 3.1.2   设置TortoiseGit记住github用户名和密码，不用每次都输入

![1558812467636](D:\cloneCode\NOTE\git使用\1558812467636.png)

![1558812515405](D:\cloneCode\NOTE\git使用\1558812515405.png)

最后内容修改为：

[credential]

　　helper = store

#### 3.1.3 设置可以ssh操作（否则Tortoise只能https方式访问）

- 设置为Git安装目录下的ssh.exe1

![1558812662333](D:\cloneCode\NOTE\git使用\1558812662333.png)













