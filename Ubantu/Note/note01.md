## 认识计算机
### 计算机的组成
> 计算机组成指的是系统结构的逻辑实现，包括机器机内的数据流和控制流的组成及逻辑设计等。主要分为五个部分：控制器，运算器，存储器，输入设备，输出设备。   

- 控制器(Control)：是整个计算机的中枢神经，其功能是对程序规定的控制信息进行解释，根据其要求进行控制，调度程序、数据、地址，协调计算机各部分工作及内存与外设的访问等
- 运算器(Datapath)：运算器的功能是对数据进行各种算术运算和逻辑运算，即对数据进行加工处理
- 存储器(Memory)：存储器的功能是存储程序、数据和各种信号、命令等信息，并在需要时提供这些信息
- 输入(Input system)：输入设备是计算机的重要组成部分，输入设备与输出设备合称为外部设备，简称外设，输入设备的作用是将程序、原始数据、文字、字符、控制命令或现场采集的数据等信息输入到计算机。常见的输入设备有键盘、鼠标器、光电输入机、磁带机、磁盘机、光盘机等
- 输出(Output system)：输出设备与输入设备同样是计算机的重要组成部分，它把外算机的中间结果或最后结果、机内的各种数据符号及文字或各种控制信号等信息输出出来。微机常用的输出设备有显示终端CRT、打印机、激光印字机、绘图仪及磁带、光盘机等
    - cpu=控制器+运算器
    - 主板=I/O总线，输入输出系统
    - 存储器=内存+硬盘
    - I/O设备：键盘,鼠标，扫描仪，显示器等等
### 计算机的工作原理
![总览](http://a3.qpic.cn/psb?/V118JuTr0BKcy7/cJWQOXkLNB.j3sR9mZdwVFUHfSJ7MoD91CJfnUedCds!/b/dPIAAAAAAAAA&bo=WwOAAgAAAAADB*g!&rf=viewer_4)

### 操作系统
> 操作系统位于【底层硬件】和【应用程序】之间，向下管理硬件资源，向上提供高级接口。在CPU的计算能力之上，操作系统提供了调度的能力，来运行进程、显示图画、响应事件。
## 认识Linux
### 操作系统的发展历史
1. 美国 - 贝尔实验室 - Thompson(肯·汤普逊)为了消遣写出了`Unix`的原型
2. 贝尔实验室 - Thompson(肯·汤普逊)和Dennis Ritchie（丹尼斯·里奇）用C语言写出`Unix`操作系统
3. Tanenbaum(塔能鲍姆）为了方便教学在`Unix`基础上写出了`Minix`
4. Torvalds（林纳斯·托瓦兹）在`Minix`的基础上写出了`Linux`
5. `Linux`开源由世界各地的程序员完善，它的图标的是`企鹅`
### Linux不同版本及应用领域
![Linux发展](http://a3.qpic.cn/psb?/V118JuTr0BKcy7/PSWKF4LzL8t6NzghMmjWzjavW94naeieYsC9DJDwzXc!/b/dPIAAAAAAAAA&bo=egOAAgAAAAADB9k!&rf=viewer_4)

- Ubuntu（友帮拓、优般图、乌班图）是一个以桌面应用为主的开源GNU/Linux操作系统，Ubuntu 是基于Debian GNU/Linux，支持x86、amd64（即x64）和ppc架构，由全球化的专业开发团队（Canonical Ltd）打造的。
- Red Hat公司发布的面向企业用户的Linux操作系统。
- SUSE(发音 /ˈsuːsə/)是指SUSE Linux ，是德国 SuSE Linux AG公司发行维护的Linux发行版，是属于此公司的注册商标。第一个版本出现在1994年年初。2004年这家公司被Novell公司收购。
- Fedora 是一个 Linux 发行版，是一款由全球社区爱好者构建的面向日常应用的快速、稳定、强大的操作系统。它允许任何人自由地使用、修改和重发布，无论现在还是将来。它由一个强大的社群开发，这个社群的成员以自己的不懈努力，提供并维护自由、开放源码的软件和开放的标准。Fedora 项目由 Fedora 基金会管理和控制，得到了 Red Hat 的支持。
#### Linux内核版本
> 内核(kernel)是系统的心脏，是运行程序和管理像磁盘和打印机等硬件设备的核心程序，它提供了一个在裸设备与应用程序间的抽象层。
- Linux内核版本又分为稳定版和开发版，两种版本是相互关联，相互循环
    - 稳定版：具有工业级强度，可以广泛地应用和部署。新的稳定版相对于较旧的只是修正一些bug或加入一些新的驱动程序。
    - 开发版：由于要试验各种解决方案，所以变化很快
- Linux发行版本
    - Linux发行版 (也被叫做 GNU/Linux 发行版) 通常包含了包括桌面环境、办公套件、媒体播放器、数据库等应用软件。

科普`GNU`计划
> GNU计划，又称革奴计划，是由Richard Stallman在1983年9月27日公开发起的。它的目标是创建一套完全自由的操作系统。Richard Stallman最早是在net.unix-wizards新闻组上公布该消息，并附带《GNU宣言》等解释为何发起该计划的文章，其中一个理由就是要“重现当年软件界合作互助的团结精神”。为保证GNU软件可以自由地“使用、复制、修改和发布”，所有GNU软件都有一份在禁止其他人添加任何限制的情况下授权所有权利给任何人的协议条款，GNU通用公共许可证（GNU General Public License，GPL）。即“反版权”（或称Copyleft）概念。
#### 应用领域
1. 个人桌面领域的应用
此领域是传统linux应用最薄弱的环节，传统linux由于界面简单、操作复杂、应用软件少的缺点，一直被windows所压制，但近些年来随着ubuntu、fedora等优秀桌面环境的兴起，同时各大硬件厂商对其支持的加大，linux在个人桌面领域的占有率在逐渐的提高
- 典型代表
    - ubuntu
    - fedora 
    - suse linux
2. 服务器领域
- linux在服务器领域的应用是其重要分支
- linux免费、稳定、高效等特点在这里得到了很好的体现，但早期因为维护、运行等原因同样受到了很大的限制，但近些年来linux服务器市场得到了飞速的提升，尤其在一些高端领域尤为广泛
- 典型代表
    - Red Hat公司的AS系列
    - 完全开源的debian系列
    - suse EnterPrise 11系列
3. 嵌入式领域
- 智能硬件
    - 近些年来linux在嵌入式领域的应用得到了飞速的提高
    - linux运行稳定、对网络的良好支持性、低成本，且可以根据需要进行软件裁剪，内核最小可以达到几百KB等特点，使其近些年来在嵌入式领域的应用得到非常大的提高
- 主要应用：机顶盒、数字电视、网络电话、程控交换机、手机、PDA、智能家居、智能硬件等都是其应用领域，得到了摩托罗拉、三星、NEC、Google等公司的大力推广
### 目录
- 在 Linux 下，我们是看不到Windows中的驱动器盘符，我们看到的是文件夹（目录）
- Linux只有一个根目录/，所有文件都在它下面，这里罗列一些常见的目录
    - /：根目录，一般根目录下只存放目录，在Linux下有且只有一个根目录。所有的东西都是从这里开始。当你在终端里输入“/home”，你其实是在告诉电脑，先从/（根目录）开始，再进入到home目录。
    - /bin: 可执行二进制文件的目录，程序就安装在这个目录，如常用的命令ls、tar、mv、cat等。
    - /boot：（引导的意思）放置linux系统启动时用到的一些文件，如果删除了，电脑有又可能启动不了，如Linux的内核文件：/boot/vmlinuz，系统引导管理器：/boot/grub。
    - /dev：存放linux系统下的设备文件，访问该目录下某个文件，相当于访问某个设备，常用的是挂载光驱 mount /dev/cdrom /mnt。
    - /home：系统默认的用户家目录，新增用户账号时，用户的家目录都存放在此目录下，/home/~表示当前用户的家目录，/home/edu 表示用户 edu 的家目录。注意，以后你要做任何事情建议都在这里做，其他目录不要随便删除。
    - /root：系统管理员root的家目录。
    - /proc：此目录的数据都在内存中，如系统核心，外部设备，网络状态，由于数据都存放于内存中，所以不占用磁盘空间，比较重要的目录有 /proc/cpuinfo、/proc/interrupts、/proc/dma、/proc/ioports、/proc/net/* 等。
### 文件权限
- 文件权限就是文件的访问控制权限，即哪些用户和组群可以访问文件以及可以执行什么样的操作。
- Unix/Linux系统是一个典型的多用户系统，不同的用户处于不同的地位，对文件和目录有不同的访问权限。为了保护系统的安全性，Unix/Linux系统除了对用户权限作了严格的界定外，还在用户身份认证、访问控制、传输安全、文件读写权限等方面作了周密的控制。
- 在 Unix/Linux中的每一个文件或目录都包含有访问权限，这些访问权限决定了谁能访问和如何访问这些文件和目录。
    
![示意图](http://a3.qpic.cn/psb?/V118JuTr0BKcy7/6gEJA9*i0F9*lBIPftf501fTg4T7cN8w9aiyWpZJ4iM!/b/dPIAAAAAAAAA&bo=MQSAAgAAAAADB5U!&rf=viewer_4)

>第1个字母代表文件的类型：“d” 代表文件夹、“-” 代表普通文件。 后 9 个字母分别代表三组权限：文件所有者、用户者、其他用户拥有的权限  

- 每一个用户都有它自身的读、写和执行权限。
   - 第一组权限控制访问自己的文件权限，即所有者权限。
   - 第二组权限控制用户组访问其中一个用户的文件的权限。
   - 第三组权限控制其他所有用户访问一个用户的文件的权限。

- 读权限（r） 对文件而言，具有读取文件内容的权限；对目录来说，具有浏览目录的权限
- 写权限（w） 对文件而言，具有新增、修改文件内容的权限；对目录来说，具有删除、移动目录内文件的权限。
- 可执行权限（x） 对文件而言，具有执行文件的权限；对目录来说该用户具有进入目录的权限。
**注意** ：通常，Unix/Linux系统只允许文件的属主(所有者)或超级用户改变文件的读写权限。

### 相对路径和绝对路径
- 绝对路径
    - cd /home
    - ls /usr
- 相对路径
    - cd ../../
### Linux命令概述
#### 命令的使用方法
- 基本命令
    - 打开控制台快捷键：Ctrl+Alt+T，同一个窗口打开：ctrl+shift+t
    - 控制台文字调大：Ctrl+Shift++（Ctrl键加上Shift加载+号）
    - 控制台文字调小：Ctrl+-（（Ctrl键加上减号）
    - 多个命令间;隔开
    - 清除屏幕：clear或者ctrl+l
    - 键盘tab键自动补全
    - pwd查看当前目录
    - 列出你敲过的命令：history ,执行历史命令的某个命令：！编号
- Linux命令格式:    
  - command  [-options]  [parameter1]  …
  - 例：ls  -ahl  /home/atguigu 
- 说明：
    - command: 命令名,相应功能的英文单词或单词的缩写 [-options]：选项,可用来对命令进行控制，也可以省略，[]代表可选 parameter1 …：传给命令的参数：可以是零个一个或多个
#### `cd`命令
> cd是change dir 简称，用于切换目录

- 切换目录：cd 要切换的目录名称 - 中间的空格不能省略
- 回到家目录：cd ~
- 回到上级目录：cd .. ，当前目录 cd .
- 切换上次所在目录：cd -
- 切换到根目录: cd /
#### 创建和删除
- 创建
    - 创建文件：touch 文件名，例如touch test.txt
    - 创建目录: mkdir 目录名称，例如：mkdir test
    - 创建多级目录命令：mkdir a/b/c -p - 参数-p可递归创建目录
    - 删除多级目录 ： rmdir a/b/c/e -p - 目录必须为空目录
    - 删除目录或文件 ：rm - 文件删除后不能恢复

![常用参数](http://a1.qpic.cn/psb?/V118JuTr0BKcy7/xIf8XbZgSCEPuUprDxVwqBEhohQU2OZcJmak*XNclz8!/b/dPMAAAAAAAAA&bo=aASwAQAAAAADB*8!&rf=viewer_4)  

#### 查看文件信息：ls
- ls -a 把所有文件和目录列出来，包含隐藏的文件和目录。
- ls -l 把文件和文件夹列表方式列出;
- ls -lh或者ls -l -h 把把文件和文件夹列表方式列出，并且显示大小；
- ls -lha或者ls -l -h -a 把所有文件夹和文件（包括隐藏的）列表方式列出，并且包含大小
    
![常用参数](http://a1.qpic.cn/psb?/V118JuTr0BKcy7/I9SOnKhpYx9yItvP3o2jU91.m0MTTTZAEY.3lMIPcls!/b/dPMAAAAAAAAA&bo=tAQqAgAAAAADB7o!&rf=viewer_4)
   
> Linux文件或者目录名称最长可以有265个字符，“.”代表当前目录，“..”代表上一级目录，以“.”开头的文件为隐藏文件，需要用 -a 参数才能显示。  

#### 通配符
`*`可以代表多个或者一个，这就是通配符,其实就是正则表达式    
![](http://a3.qpic.cn/psb?/V118JuTr0BKcy7/IajfXT4Xh8mGnfN3JAaaLtweEoMEWl.i.bu3LuAnKu4!/b/dPIAAAAAAAAA&bo=gAKgAgAAAAADAAU!&rf=viewer_4)     
![](http://a2.qpic.cn/psb?/V118JuTr0BKcy7/mGZ8r84CQfVl0Fpx1ImwAqI0xyUTE0Q*n9RzD6VLbKE!/b/dD8BAAAAAAAA&bo=YAOAAgAAAAADAMQ!&rf=viewer_4)     
#### 输出重定向命令：> & >>
- Linux允许将命令执行结果重定向到一个文件，本应显示在终端上的内容保存到指定文件中
    - ls > test.txt ( test.txt 如果不存在，则创建，存在则覆盖其内容 )
    - ls >> test.txt (会将内容添加到文档原本内容的最后)
- 注意：>输出重定向会覆盖原来的内容，>>输出重定向则会追加到文件的尾部。
#### 强制结束程序
- Ctrl-C送SIGINT信号，默认进程会结束，但是进程自己可以重定义收到这个信号的行为
- Ctrl-Z送SIGSTOP信号，进程只是被停止，再送SIGCONT信号，进程继续运行
#### 查看帮助文档--help
- --help
    - 一般是linux命令自带的帮助信息
    - 如：ls --help
- man(手册，manual)
    - man是linux提供的一个手册，包含了绝大部分的命令、函数使用说明
      该手册分成很多章节（section），使用man时可以指定不同的章节来浏览
    - 例：man ls ; man  printf
- man中各个section意义如下：
    - Standard commands（标准命令）
    - System calls（系统调用，如open,write）
    - Library functions（库函数，如printf,fopen）
    - Special devices（设备文件的说明，/dev下各种设备）
    - File formats（文件格式，如passwd）
    - Games and toys（游戏和娱乐）
    - Miscellaneous（杂项、惯例与协定等，例如Linux档案系统、网络协定、ASCII 码；environ全局变量）
    - Administrative Commands（管理员命令，如ifconfig）
- man是按照手册的章节号的顺序进行搜索的。
 - 注意：实际上，我们不用指定第几个章节也用查看，如，man ls
![](http://a1.qpic.cn/psb?/V118JuTr0BKcy7/yL.KibCpDmOJ6skJFN7xEyT.HPOncKxSyqzQszH8MIU!/b/dD4BAAAAAAAA&bo=3ATYAAAAAAADACU!&rf=viewer_4)    
![](http://a1.qpic.cn/psb?/V118JuTr0BKcy7/Ne7G3I3sZ9UfVIjtM7WhZpWyMpB9nYCdnMDp1jgqZm0!/b/dD4BAAAAAAAA&bo=mQOAAgAAAAADAD0!&rf=viewer_4)  
#### 分屏显示more
> 查看内容时，在信息过长无法在一屏上显示时，会出现快速滚屏，使得用户无法看清文件的内容，此时可以使用more命令，每次只显示一页，按下空格键可以显示下一页，按下q键退出显示，按下h键可以获取帮助,b返回上一页，f显示下一页。
#### 管道`|`
- 一个命令的输出可以通过管道做为另一个命令的输入 
- 管道我们可以理解现实生活中的管子，管子的一头塞东西进去，另一头取出来，这里“ | ”的左右分为两端，左端塞东西(写)，右端取东西(读)。
- 命令如下：ls -lah | more
#### 打开文本的工具
- sublime text，打开命令：subl 文件名,例如命令：subl haha.txt
- cat命令 cat文件名，例如： cat haha.txt
- gedit文本工具 ，例如： gedit haha.txt
- vim,vi,打开文本例如,vi haha.txt 或者vim haha.txt
#### 普通用户切换到root账号
- sudo -s,如果切换到root账号了，会从$变成#
- 退出：exit
#### 获取文件所有权限
- chmod 777 文件名（包含后缀）











