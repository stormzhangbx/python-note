# virtualenv

## 一 安装

通过pip

`pip3 install virtualenv`

## 二 使用

**1 新建项目**

新建一个项目目录virtualenvdemo

**2 新建一套独立的、隔离的Python运行环境**

virtualenv包会被安装到`D:\Python38\Lib\site-packages`目录下，同时`virtualenv.exe`命令会被安装到`D:\Python38\Scripts`目录下，因此可以在命令行中直接运行`virtualenv`

运行cmd，在virtualenv目录下运行`virtualenv --no-site-packages venv`，会在项目下生成venv目录，里面包含Include、Lib、Scripts、tcl、LICENSE.txt等目录文件，可以发现，在`D:\Python38`下也有类似的这些文件目录

执行`venv\Scripts\active`，即可进入该环境，注意到命令提示符变了，有个`(venv)`前缀，表示当前环境是一个名为`venv`的Python环境

执行`venv\Scripts\deactivate`，即可退出该环境，即回到了正常的环境，现在`pip3`或`python`均是在系统Python环境下执行

**3 在新环境中安装python依赖**

此时通过pipy安装的Python依赖包，都是放到了`E:\python\virtualenvdemo\venv\Lib\site-packages`目录中

## 三 注意

如果用PyCharm打开virtualenvdemo项目，右键项目virtualenvdemo -> Open in Terminal，打开PyCharm终端，会自动进入venv环境

[Linux 如何使用 virtualenv](https://www.cnblogs.com/yanzhi-1996/articles/11100765.html)