# note

在刚开始学习Python时发现有3个工具需要重点理解和掌握。

## 1 解释器Python

即需要在系统中安装Python。

## 2 包管理工具pip

pip 是 Python 包管理工具，该工具提供了对Python 包的查找、下载、安装、卸载的功能。类似Node中的npm，Java中的Maven，Linux中的RPM、yum

## 3 创建独立的Python运行环境virtualenv

在没有创建独立环境时，通过pip安装的包都放在D:\Python38\Lib\site-packages（这是Window环境，Linux环境是/usr/local/python3/lib/python3.8/site-packages）目录下，这种场景对于只开发一个Python项目是没问题的，但对于开发多个Python项目这是不可行的。如项目A需要依赖xxx 1.0，而项目B需要依赖xxx 1.8。此时就需要为每个Python项目创建独立的运行环境。

类似问题其他语言解决方案：

- Node: 每个node项目根目录都有一个node_modules文件夹，用于存放该项目所需的依赖包。
- Java: 虽然Java项目项目的依赖都存在与一个地方，即本地的依赖仓库，但仓库可以存放同一个依赖的不同版本。项目中需要写明依赖的版本号。
