# cocos2d-x3.0rc-win10-android-
cocos2d-x 3.0rc+win10


win8下cocos2d-x的环境配置及项目创建楼主在网上找了好多个3.0以上版本的配置教程来看，从3.0到3.9几乎都试过了，好吧，最终还是3.0好。

· 主要要感谢这个博主的教程http://blog.csdn.net/linzhengqun/article/details/21663341 其实按照这个博主的配置过程来说应该是没有什么问题的，然后比较主要的就是在后面项目。

配置过程
·具体配置过程可以看以上博主的

JDK配置问题

JAVA_HOME:C:\Program Files (x86)\Java\jdk1.7.0_21(JAVA安装的路径)

CLASSPATH:可以不要

Path:C:\Program Files (x86)\Java\jdk1.7.0_21\bin(bin的路径)



项目创建
进入到cocos2d-x->tools->cocos2d-console->bin这个文件夹中，按住shift，右键，打开命令窗口，
输入： python cocos.py new [文件名] -p com.[随意名字].[包名]  -l cpp
例如： python cocos.py new HelloWorld -p com.coddM.hello -l cpp
可以在bin中看到创建好的HelloWorld程序。

到此文件就创建成功啦，之后再更新android工程的创建以及cocos2d-x写游戏的问题。
