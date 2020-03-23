# 制作安卓apk文件
前期需安装好unity，后边需要用到

1-配置电脑环境变量：
* 查看Java 安装路径
![1]
2-新建变量：变量值为Java安装路径
![2]
3-在path后加%JAVA_HOME%\bin
![3]
4-验证是否成功安装Java
命令输入：java
输出成功如图：
![4]
5-安装sdk（Andriod开发包）
软件：android-sdk_r24.4.1-windows
![5]
6-打开unity，新建一个项目，打开Edit-Preferences选项
![6]
* 完成后，新建场景，保存场景，添加到build里面去切换平台为安卓Android平台
File-build setting 
![7]
![8]
* Player settings修改Other Settings 
BundleIdentifiercom.Company.ProductName自定义name，例如：com.cym.sj，点击Build，打包
![10]
7-打包完成后，在手机设备中安装即可开启游戏
