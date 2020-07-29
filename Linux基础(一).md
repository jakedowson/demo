# Linux基础(一)

## 一:Linux概述

### 1. Linux的概述

####  Unix

```
Unix是一个强大的多用户、多任务操作系统。 于1969年在AT&T的贝尔实验室开发。 UNIX的商标权由国际开放标准组织（The Open Group）所拥有。 UNIX操作系统是商业版，需要收费，价格比Microsoft Windows正版要贵一些。
```

#### 简介

```
Linux是一套免费使用和自由传播的类Unix操作系统，是一个基于POSIX和UNIX的多用户、多任务、支持多线程和多CPU的操作系统。它能运行主要的UNIX工具软件、应用程序和网络协议。它支持32位和64位硬件。Linux继承了Unix以网络为核心的设计思想，是一个性能稳定的多用户网络操作系统。

严格来讲，Linux这个词本身只表示Linux内核，但实际上人们已经习惯了用Linux来形容整个基于Linux内核，并且使用GNU工程各种工具和数据库的操作系统。
```

#### 历史

```
Linux最初是由芬兰赫尔辛基大学学生Linus Torvalds由于自己不满意教学中使用的MINIX操作系统， 所以在1990年底由于个人爱好设计出了LINUX系统核心。后来发布于芬兰最大的ftp服务器上，用户可以免费下载，所以它的周边的程序越来越多，Linux本身也逐渐发展壮大起来，之后Linux在不到三年的时间里成为了一个功能完善，稳定可靠的操作系统.
```

![åå§äººæçº³æ¯Â·æç¦å¹](assets/96dda144ad345982b3b0bcdb0df431adcbef8444.jpg)

#### 版本

```
Linux的版本分为两种：内核版本和发行版本
内核版本是指在Linus领导下的内核小组开发维护的系统内核的版本号  
发行版本是指一些组织和公司根据自己发行版的不同而自定的 
```

主流版本

![1548055765804](assets/1548055765804.png)



#### 应用

```
Linux的运用非常广泛
服务器系统:Web应用服务器、数据库服务器、DNS、FTP等等；
嵌入式系统:路由器、分享器、交换器、家电用品的微电脑控制器等等，
运算服务器:高性能运算、计算密集型应用
桌面应用系统
移动手持系统
```

### 2. Linux和windows差异

#### 系统核心

```
windows和linux的本质区别是核心的不同,windows是从早期的dos经过比尔盖茨开发来的,linux是由李纳斯最早从unix上开发出来的
```

#### 授权方式

```
windows是微软公司的产品，版权在微软公司
linux遵循GNU，是开放免费的软件.
```

#### 交互方式

```
windows主要是通过图形界面的方式和用户交互的，图形界面会占用比较多的资源
linux的用户企业用户大部分时候是远程操作，用命令行的时候比较多,对资源的消耗比较少
```

#### 应用领域

```
windows目前主要的应用应该是PC机，或者说是家用的普通办公电脑。
linux更多的用于企业的服务器或者网络设备等。
```



## 二:软件安装

### 1. VMware安装

#### 简介

```
什么是虚拟软件：
    虚拟原件是一个可以使你在一台机器上同时运行二个或更多Windows、LINUX等系统。它可以模拟一个标准PC环境。这个环境和真实的计算机一样，都有芯片组、CPU、内存、显卡、声卡、网卡、软驱、硬盘、光驱、串口、并口、USB控制器等

常用的虚拟原件：
    1.VMware workstation
    2.VirtualBox
```

#### 安装

1. 运行`VMware-workstation-full-12.5.4-5192485.exe`程序

   ![img](assets/markdown-img-paste-20180821105859345.png)

2. 点击下一步进行安装

   ![img](assets/markdown-img-paste-20180821110925469.png)

3. 勾选接收许可协议,点击下一步继续

   ![img](assets/markdown-img-paste-20180821110902413.png)

4. 选择安装目录,注意不要安装在中文及特殊符号目录下

   ![img](assets/markdown-img-paste-20180821111127919.png)

5. 用户体验设置,点击下一步继续

   ![img](assets/markdown-img-paste-20180821111155818.png)

6. 选择是否创建快捷方式

   ![img](assets/markdown-img-paste-20180821111241406.png)

7. 点击安装

   ![img](assets/markdown-img-paste-20180821111500359.png)

8. 点击许可证

   ![img](assets/markdown-img-paste-20180821111656156.png)

9. 输入密钥,完成激活

   ![img](assets/markdown-img-paste-20180821111742423.png)

10. 打开网络适配器,如果有如下二张网卡,代表安装成功

    ![img](assets/markdown-img-paste-20180821112335779.png)



### 2. CentOS安装

#### 简介

```
CentOS（Community Enterprise Operating System，中文意思是：社区企业操作系统）是Linux发行版之一，它是来自于Red Hat Enterprise Linux依照开放源代码规定释出的源代码所编译而成。由于出自同样的源代码，因此有些要求高度稳定性的服务器以CentOS替代商业版的Red Hat Enterprise Linux使用。两者的不同，在于CentOS并不包含封闭源代码软件。
```

#### 安装

1. 点击`创建新的虚拟机`图标

   ![img](assets/markdown-img-paste-20180821112911715.png)

2. 选择 典型（推荐）→ 下一步

   ![img](assets/markdown-img-paste-20180821112951495.png)

3. 选择稍后安装操作系统

   ![img](assets/markdown-img-paste-20180821113015618.png)

4. 选择操作系统和版本

   ![img](assets/markdown-img-paste-20180821113052277.png)

5. 输入虚拟机名称和安装路径

   ![img](assets/markdown-img-paste-20180821113239181.png)

6. 设置磁盘大小

   ![img](assets/markdown-img-paste-20180821113303294.png)

7. 自定义硬件

   ![img](assets/markdown-img-paste-2018082111333086.png)

8. 选择CentOS安装镜像文件

   ![img](assets/markdown-img-paste-20180821113437100.png)

9. 点击完成

   ![img](assets/markdown-img-paste-20180821113456675.png)

10. 启动虚拟机

    ![img](assets/markdown-img-paste-20180821113522325.png)

11. 选择第一项，安装全新操作系统或升级现有操作系统

    ![img](assets/markdown-img-paste-20180821113648887.png)

12. 使用`Tab`键进行选择，选择`Skip`，退出检测

    ![img](assets/markdown-img-paste-20180821113722403.png)

13. 点击Next

    ![img](assets/markdown-img-paste-20180821113812815.png)

14. 选择语言，这里选择的是中文简体

    ![img](assets/markdown-img-paste-20180821113843308.png)

15. 选择键盘样式

    ![img](assets/markdown-img-paste-20180821113906759.png)

16. 选择存储设备

    ![img](assets/markdown-img-paste-20180821113928850.png)

    ![img](assets/markdown-img-paste-20180821114010227.png)

17. 输入主机名

    ![img](assets/markdown-img-paste-20180821114044548.png)

18. 配置网络

    ![img](assets/markdown-img-paste-20180821114121804.png)

    ![img](assets/markdown-img-paste-2018082111414734.png)

19. 设置时区，勾选使用UTC时间

    ![img](assets/markdown-img-paste-2018082111422039.png)

20. 输入根用户（root）的密码

    ![img](assets/markdown-img-paste-20180821114339488.png)

21. 根据此Linux具体功能，选择不同的方式

    ![img](assets/markdown-img-paste-20180821114410336.png)

    ![img](assets/markdown-img-paste-20180821114430835.png)

22. 选择安装的Linux版本

    ![img](assets/markdown-img-paste-20180821114642369.png)

23. 安装中

    ![img](assets/markdown-img-paste-20180821114707202.png)

24. 重新引导

    ![img](assets/markdown-img-paste-20180821122439601.png)

25. 输入用户名和密码登录

    ![1548061572178](assets/1548061572178.png)

### 3. putty安装

#### 简介

```
PuTTY是一个SSH和telnet客户端，最初由Simon Tatham为Windows平台开发。PuTTY是一个开源软件，提供源代码，由一组志愿者开发和支持。
```

#### 下载

```
网站地址:https://www.putty.org/
下载地址:https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
```

![1548058235975](assets/1548058235975.png)

#### 安装

1. 双击运行安装程序

   ![1548059042954](assets/1548059042954.png)

   ![1548059107350](assets/1548059107350.png)

2. 点击`next`开启安装

   ![1548059168088](assets/1548059168088.png)

3. 选择安装路径

   ![1548059225846](assets/1548059225846.png)

   ![1548059264583](assets/1548059264583.png)

4. 选择安装桌面快捷方式

   ![1548059678415](assets/1548059678415.png)

   5. 点击`install`开始安装

      ![1548059752819](assets/1548059752819.png)

#### 连接

1. 双击打开程序

   ![1548061928652](assets/1548061928652.png)

2. 查看`CentOS`的`IP`地址

   ![1548062005939](assets/1548062005939.png)

3. 输入IP地址连接`CentOS`

   ![1548062158351](assets/1548062158351.png)

4. 输入用户名和密码

   ![1548062270539](assets/1548062270539.png)

5. 配置`session`,下次连接不用再次输入IP

   ![1548062641907](assets/1548062641907.png)

   ![1548062806222](assets/1548062806222.png)

   ​		

## 三:Linux常用命令(重点)

### 1. 目录操作

Linux目录结构

![1548298026886](assets/1548298026886.png)

![img](assets/003vPl7Rty6E8kZRlAEdc690.jpg)

常用目录	

```
/root： 该目录为系统管理员，也称作超级权限者的用户主目录。
/home： 用户的主目录，在Linux中，每个用户都有一个自己的目录，一般该目录名是以用户的账号命名的。
/etc：  这个目录用来存放所有的系统管理所需要的配置文件和子目录。
/usr：  这是一个非常重要的目录，存放系统用户共享资源
```

#### 列出文件及目录

```
ls(list)是一个非常有用的命令，用来显示当前目录下的内容。配合参数的使用，能以不同的方式显示目录内容。     
格式：ls [参数] [路径或文件名]
参数:
	-a	显示所有文件或目录（包含隐藏的文件）
	-l	显示文件详细信息 
常用：
    在linux中以 . 开头的文件都是隐藏的文件
    ls
    ls -a  		显示所有文件或目录（包含隐藏的文件）
    ls -l  		列出当前目录下的文件列表,以详细信息展示,可以缩写为ll
    ls -l /		列出根目录下的文件列表,以详细信息展示
```



#### 切换目录

```
cd(change directory)命令可以用来切换目录

格式: cd <路径或目录名>
常用:
	cd app    	切换到app目录
    cd ..    	切换到上一层目录
    cd /        切换到系统根目录
    cd ~        切换到用户主目录
    cd -        切换到上一个所在目录
```

#### 创建目录

```
mkdir(make directory)命令可用来创建子目录。

格式: mkdir [参数] <目录路径或目录名>
参数: 
	-p	级联创建目录结构
常用:
    mkdir app   在当前目录下创建app目录
    mkdir –p app2/test  级联创建aap2以及test目
```

#### 删除目录

```
rmdir(remove directory)命令可用来删除“空”的子目录

格式: rmdir <目录路径或目录名>
常用:
    rmdir app    删除app目录
```



### 2. 文件操作

#### 查看文件内容

```
cat 用于显示文件的内容。

格式: cat [参数] <文件名>
参数:
	-n	对输出的所有行编号
常用
    cat yum.conf
    cat -n yum.conf
```

```
more 一般用于要显示的内容会超过一个画面长度的情况。按空格键显示下一个画面。回车显示下一行内容。

格式: more [参数] <文件名>
常用:
    more yum.conf
快捷键:   
    空格		翻页
    确定		下一行
    q		 退出查看
```

```
less 用法和more类似，不同的是less可以通过PgUp、PgDn键来控制上下翻页。

格式: more [参数] <文件名>
常用:
    less yum.conf
快捷键:   
    PgUp		上一页
    PgDn		下一页
    q		 	退出查看
```

```
head 查看文件的前面部分,默认显示前10行

格式: more [参数] <文件名>
参数:
	-n		显示每个文件的前n行内容
常用:	
    head yum.conf  显示文件的前10行
    head -100 yum.conf  显示文件的前100行
```

```
tail 查看文件的后面部分,默认显示最后10行

格式: tail [参数] <文件名>
参数:
	-n		显示每个文件的后n行内容
	-f		即时输出文件变化后追加的数据。
常用:	
    tail yum.conf  		显示文件的最后10行
    tail -100 yum.conf  显示文件的最后100行
    tail -f yum.conf  	显示文件的最后10行,并且监控文件的变化,输出文件变化后追加的数据。
```

#### 过滤文件内容

```
grep 查找符合条件的字符串。
格式: grep <text> [参数] <文件名>
参数:
	-i 	忽略大小写
	-n  输出的同时打印行号
	-B  显示前N行的内容
	-A	显示后N行的内容
	--color 高亮展示查询关键字
常用:	
    grep headers install.log  在文件中查找headers
    grep  -B 10 headers  install.log   在文件中查找headers,显示前10行的内容
    grep  -A 10 headers  install.log   在文件中查找headers,显示后10行的内容
    grep  -A 10 --color headers  install.log  在文件中查找headers,高亮展示关键字
```

#### 创建空文件

```
touch 用于创建一个空文件

格式: touch <文件名>
常用:
	touch aa.txt
```

#### 删除文件

```
rm 用于删除文件或者目录

格式: rm [参数] <文件名>
参数:
	-f  	强制删除。忽略不存在的文件，不提示确认
	-r		递归删除目录及其内容
常用:
    rm 	a.txt    	删除a.txt文件,输入y/n,y确认删除,n不删除
    rm -f   a.txt   不询问，直接删除
    rm -r   aa    	删除aa目录,每个目录及文件都提示
    rm -rf  aa    	不询问递归删除aa目录
    rm -rf  *      	删除当前目录下所有文件
    rm -rf  /*      删除根目录下所有文件(自杀)
```

#### 文件编辑

```
vi/vim 用于编辑文件, 一共有三种模式：命令行模式、插入模式、底行模式。

格式: vi/vim [参数] <文件名>

命令行模式: 用户在命令行模式可以按一些快捷键达到快速输入的目的,例如复制,粘贴,删除,插入等
插入模式: 用户可以在插入模式对文件内容进行编辑
底行模式: 用户可以底行模式输入一些命令,对文件进行操作,例如:保存退出,不保存退出,查找等

用户使用vi/vim命令编辑文件,刚开始进入到命令行模式,之后可以使用命令来切换模式

命令行模式-->插入模式: 
    i 在当前位置插入
    I 在当前行首插入
    a 在当前位置后插入
    A 在当前行尾插入
    o 在当前行之后插入一行
    O 在当前行之前插入一行

插入模式-->命令行模式:
	Esc 从插入模式切换到命令行模式

命令行模式-->底行模式:
	:（冒号） 从命令行模式切换到底行模式

命令行模式快捷键:
	dd 	快速删除一行
    yy 	拷贝当前行
	nyy 拷贝当前后开始的n行，比如2yy拷贝当前行及其下一行。
	p  	在当前光标后粘贴,如果之前使用了yy命令来复制一行，那么就在当前行的下一行粘贴。
	P 	在当前行前粘贴

底行模式命令:
	wq	保存退出
	q!	强制退出并忽略所有更改
	e! 	放弃所有修改，并打开原来文件。
	/text 	查找text，按n健查找下一个，按N健查找前一个。

```

### 3. 通用文件或目录操作

#### 复制文件或目录

```
cp(copy) 将源文件复制至目标文件，或将多个源文件复制至目标目录。

格式: cp [参数] 源目录或文件 目标目录或文件
参数:
	-r		递归复制目录及其子目录内的所有内容
常用:
    cp install.log install.log.bak   	将install.log复制为install.log.bak文件
    cp install.log aaa/   	 			将install.log文件复制到当前目录下的aaa目录下
    cp install.log bbb/install.log.bak  将install.log文件复制到当前目录下的bbb目录下,改名为install.log.bak
    cp aaa -r  bbb/  	  				递归复制aaa目录及子目录的所有内容到bbb目录下
    cp aaa -r  bbb/ccc                  递归复制aaa目录及子目录的所有内容到bbb目录下,改名为ccc
    

复制文件,如果后一个参数是目录,则复制文件到指定目录
复制文件,如果后一个参数是文件,则复制文件到指定路径,并改名
复制目录,如果后一个参数是已经存在的目录,则复制目录到指定目录下
复制目录,如果后一个参数是不存在的目录,则复制目录到指定路径下,并改名
```

#### 移动文件或目录

```
mv(move) 将源文件重命名为目标文件，或将源文件移动至指定目录。

格式: mv 源目录或文件 目标目录或文件
常用: 
    mv install.log install.log.bak   	将install.log重命名为install.log.bak
    mv install.log aaa/   	 			将install.log文件移动到当前目录下的aaa目录下
    mv install.log bbb/install.log.bak  将install.log文件移动到当前目录下的bbb目录下,改名为install.log.bak
    mv aaa  bbb/  	  					将aaa目录移动到bbb目录下
    mv aaa  bbb/ccc                     将aaa目录移动到bbb目录下,重命名为ccc
   
   
移动文件,如果后一个参数是目录,则移动文件到指定目录
移动文件,如果后一个参数是文件,则移动文件到指定路径,并重命名
移动目录,如果后一个参数是已经存在的目录,则移动目录到指定目录下
移动目录,如果后一个参数是不存在的目录,则移动目录到指定路径下,并重命名
```

#### 打包压缩和解压缩

```
tar 命令能够将用户所指定的文件或目录打包成一个文件，但不做压缩。一般Linux上常用的压缩方式是选用tar将许多文件打包成一个文件，再以gzip压缩命令压缩成xxx.tar.gz(或称为xxx.tgz)的文件。  

格式: tar [参数] <文件或目录列表>
参数：
    -c:	创建一个新tar文件
    -v:	显示运行过程的信息
    -f:	指定文件名
    -z:	调用gzip压缩命令进行压缩
    -x:	解开tar文件
    -C:	指定解压路径
常用:
		tar –cvf aaa.tar ./*		将当前目录下的所有文件打包为aaa.tar
    tar –zcvf aaa.tar.gz ./*	将当前目录下的所有文件打包压缩为aaa.tar.gz
    tar –xvf aaa.tar			将aaa.tar提取到当前目录
    tar -xvf aaa.tar.gz -C /usr/aaa		将aaa.tar.gz解压到/usr/aaa目录
    
```

### 4. 其他常用命令

#### 重定向输出

```
> 	重定向输出，覆盖原有内容
>> 	重定向输出，又追加功能

常用：
  ifconfig > ifconfig.txt   将ifconfig命令的结果输出到 ifconfig.txt文件中
  ifconfig >> ifconfig.txt   将ifconfig命令的结果追加到 ifconfig.txt文件中
```

#### 管道

```
管道是Linux命令中重要的一个概念，其作用是将一个命令的输出用作另一个命令的输入。
示例:
  ls --help | more    分页查询帮助信息
  ps –ef | grep java  查询名称中包含java的进程
```

#### 其他

```
1. pwd 		查看当前工作目录    
2. ll -h  	友好显示文件大小	
3. wget		下载资料          
```
