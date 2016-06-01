# path_configuration

# Mac中配置环境变量
一、配置
1.查找环境变量
set | grep Path (区分大小写)
2.找到Path路径 --- 以“:”区分
Path = /usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:
3.进入环境变量文件
sudo vi /etc/bashrc 输入密码；申请权限处理
4.环境变量文件内
使用i.进入编辑状态；
使用esc.退出编辑状态；
使用u.返回上级操作；
使用:wq!.退出保存；

二、使用
1.JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_65.jdk/Contents/Home
$JAVA_HOME/bin:
$JAVA_HOME/jre/bin:
CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar

2.ANDROID_HOME=/Users/admin/Documents/tool/android/SDK/sdk
$ANDROID_HOME/platform-tools:
$ANDROID_HOME/tools:

3.NODE_HOME=/usr/local/bin/node:/usr/local/bin/npm
$NODE_HOME:

4.ANT_HOME=/Users/admin/Documents/tool/android/apache-ant-1.9.7
$ANT_HOME/bin:

PATH=/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:$JAVA_HOME/bin:$JAVA_HOME/jre/bin:$ANDROID_HOME/platform-tools:$ANDROID_HOME/tools:$ANT_HOME/bin:$NODE_HOME



# PC中配置环境变量
一、配置
我的电脑；属性；高级系统设置；环境变量；

二、使用
1.JAVA_HOME；
C:\Program Files\Java\jdk1.8.0_05

2.CLASSPATH
.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;

3.ANDROID_HOME
G:\AndroidEclipse\sdk

4.ANT_HOME
G:\apache-ant-1.9.7

5.PATH
%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;%ANDROID_HOME%\tools;%ANDROID_HOME%\platform-tools;%ANT_HOME%\bin;
