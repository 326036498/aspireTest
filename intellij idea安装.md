##intellij idea安装##

**IntelliJ IDEA官网下载地址 ：**
[https://www.jetbrains.com/idea/download/#section=windows](https://www.jetbrains.com/idea/download/#section=windows)

![IDE官网](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171205194610628-1721397153.png)

**确认已经安装好了 JDK ，比如JDK1.8**

![IDE安装步骤](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171205200348222-2064563648.png)

**选择安装路径**

![IDE选择安装路径](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171205200527425-1461784901.png)

**根据系统类型选择，32位和64位。然后选择是否根据文件后缀名关联相应的文件，例如勾选了Java以后打开java文件默认是以IDEA打开，可以全不勾选。**

![选择操作系统](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171205200554003-1282727364.png)

**点击Install，就开始安装了**

![安装](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171205200628863-1602142211.png)

**目录说明**

![目录说明](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171206122455566-1188233198.png)

- Bin：容器，执行文件和启动参数等。
- Help：快捷键文档和其他帮助文档
- Jre64:64 位 java 运行环境
- Lib：idea 依赖的类库
- License：各插件许可
- Plugin：插件

##破解方式##
1.[IntelliJ IDEA](http://idea.lanyus.com/) 注册码激活

![注册激活码](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171206100851706-229737583.png)

**2.破解补丁**

补丁下载：[https://files.cnblogs.com/files/jajian/JetbrainsCrack-2.6.10-release-enc.jar.zip](https://files.cnblogs.com/files/jajian/JetbrainsCrack-2.6.10-release-enc.jar.zip)

下载好的补丁放在安装路径的bin目录里

![目录](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171206102228581-1413761697.png)

![jar包](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171206102300722-1805618857.png)

**bin目录里有还有两个vmoptions文件，这是idea vm配置文件，分别对应32位和64位系统**

![bin目录](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171206101809722-2082076862.png)

**打开文件编辑，分别增加如下一行并保存 :**

`-javaagent:D:\mysoft\JetBrains\IntelliJ IDEA 2017.2.6\bin\JetbrainsCrack-2.6.9-release-enc.jar`

**注：D:\mysoft\JetBrains\IntelliJ IDEA 2017.2.6为IDEA的安装路径。**

**重启IDEA，此时选择‘’Activation code ‘’选项，然后在下方输入框中再次输入刚才添加的文本：-javaagent:D:\mysoft\JetBrains\IntelliJ IDEA 2017.2.6\bin\JetbrainsCrack-2.6.9-release-enc.jar**

![IDE](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171206103428394-2106376097.png)

**点击OK，破解完成，此时可看到有效期至2116年结束**

![](https://images2017.cnblogs.com/blog/1162587/201712/1162587-20171206103539534-1737255929.png)