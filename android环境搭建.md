#  Android开发  环境搭建指南
## 1 .下载地址  [http://www.androiddevtools.cn/](http://www.androiddevtools.cn/) ##

## 2 .安装前确认JDK已经安装并配置好环境变量。（jre和jdk安装目录相同）

 2.1 安装完JDK后配置环境变量  计算机→属性→高级系统设置→高级→环境变量

 2.2 系统变量→新建 JAVA_HOME 变量 。变量值填写jdk的安装目录（如 E:\Java\jdk1.8.0)

 2.3 系统变量→寻找 Path 变量→编辑，在变量值最后输入 %JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;（注意原来Path的变量值末尾有没有;号，如果没有，先输入；号再输入上面的代码）
![](http://i.imgur.com/SPqOtQ0.png)

 2.4 系统变量→新建 CLASSPATH 变量，变量值填写   .;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar（注意最前面有一点）
![](http://i.imgur.com/NnODPHy.png)

 2.5 检验是否配置成功 运行cmd 输入 java -version （java 和 -version 之间有空格）若如图所示 显示版本信息 则说明安装和配置成功。
![](http://i.imgur.com/NPYxHER.png)

----------

## 3 .下载并安装android studio 安装包 （下载的版本如android-studio-bundle-135.1740770-windows.exe，然后使用管理员身份运行。）

 3.1 在选择安装的组件时，如果你从未安装过安卓开发环境，那么建议全部选择安装，如果不了解这是什么意思，同样建议全部选择安装。

 3.2 SDK组件是占用磁盘空间大户，在选择安装路径时，不要使用默认路径。建议选择安装在剩余较多空间的磁盘，且选择一个较短的易于找到的路径。
![](http://i.imgur.com/0nRQ6X8.png)

3.3 经过上面的安装android-studio已经可以使用，如果想在命令提示符中使用SDK命令，那么还需要把SDK下的tools目录和platform-tools目录添加到环境变量中。
![](http://i.imgur.com/oGW3Bqb.png)

3.4 查看安装好的Android SDK
![](http://i.imgur.com/GNXJWZa.png)