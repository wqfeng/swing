# 环境搭建

本节指导您如何下载并在电脑上安装 Java，请按照下述步骤搭建环境。

可从 [Download Java ](http://java.sun.com/javase/downloads/index_jdk5.jsp)免费下载 Java SE，请根据您的操作系统下载对应的版本。

按照说明下载 Java，运行 .exe 文件安装 Java。安装成功后，需要设置环境变量以指向正确的安装目录：

## 在 Windows 2000/XP 上配置 Path：

假设您已将 Java 安装在目录 `c:\Program Files\java\jdk`:

- 右键单击“我的电脑”，选择“属性”。
- 在“高级”选项卡里点击“环境变量”按钮。
- 编辑 `Path` 变量，使其包含指向 Java 可执行文件的路径。比如现在的`path`设置为 `'C:\WINDOWS\SYSTEM32'`，则将其改为 `'C:\WINDOWS\SYSTEM32;c:\Program Files\java\jdk\bin'`。  

## 在 Windows 95/98/ME 上配置 Path：

假设您已将 Java 安装在目录 `c:\Program Files\java\jdk`:

- 编辑 ` 'C:\autoexec.bat'` 文件，在最后增加如下一行：  
`'SET PATH=%PATH%;C:\Program Files\java\jdk\bin'`

## 为Linux、Unix、Solaris 和 FreeBSD 上配置 Path：

环境变量 `PATH` 需要被设置为指向安装 Java 的路径，如果遇到问题，请参考 shell 文档。

比如使用 *bash*，则可以在 `.bashrc` 文件的末尾加入：`export PATH=/path/to/java:$PATH'`。

## 流行的 Java 编辑器：

您需要一个文本编辑器来编写 Java 程序，市场上也有更复杂的 IDE。但目前来说，您可以考虑如下几种：

- **记事本**——在 Windows 机器上，您可以选择任何简单的文本编辑器，比如记事本（本教程推荐编辑器）、写字板。
- **Netbeans**——Netbeans是一款开源且免费的 Java IDE，可从 [http://www.netbeans.org/index.html](http://www.netbeans.org/index.html) 下载。
- **Eclipse**——Eclipse是另外一款由 Eclipse 开源社区开发的 Java IDE，可从 [ http://www.eclipse.org/]( http://www.eclipse.org/) 下载。
