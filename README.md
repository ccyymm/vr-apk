# 制作安卓apk文件
前期需安装好unity，后边需要用到

1-配置电脑环境变量：<br>
* 查看Java 安装路径<br>
![1](https://github.com/ccyymm/vr-apk/blob/master/1.png)

2-新建变量：变量值为Java安装路径<br>
![2](https://github.com/ccyymm/vr-apk/blob/master/2.png)

3-在path后加%JAVA_HOME%\bin<br>
![3](https://github.com/ccyymm/vr-apk/blob/master/3.png)

4-验证是否成功安装Java<br>
命令输入：java
输出成功如图：<br>
![4](https://github.com/ccyymm/vr-apk/blob/master/4.png)

5-安装sdk（Andriod开发包）<br>
软件：android-sdk_r24.4.1-windows<br>
![5](https://github.com/ccyymm/vr-apk/blob/master/5.png)

6-打开unity，新建一个项目，打开Edit-Preferences选项<br>
![6](https://github.com/ccyymm/vr-apk/blob/master/6.png)

* 完成后，新建场景，保存场景，添加到build里面去切换平台为安卓Android平台<br>
File-build setting <br>
![7](https://github.com/ccyymm/vr-apk/blob/master/7.png)
![8](https://github.com/ccyymm/vr-apk/blob/master/8.png)

* Player settings修改Other Settings <br>
BundleIdentifiercom.Company.ProductName自定义name，例如：com.cym.sj，点击Build，打包<br>
![10](https://github.com/ccyymm/vr-apk/blob/master/9.png)

7-打包完成后，在手机设备中安装即可开启游戏
