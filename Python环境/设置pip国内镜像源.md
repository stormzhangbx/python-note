# 设置pip国内镜像源

在 `C:\Users\用户名\pip` 文件夹下新建`pip.ini`文件（如果pip文件夹不存在，可以自己创建），内容如下：

```ini
[global]
index-url = http://mirrors.aliyun.com/pypi/simple/
[install]
trusted-host = mirrors.aliyun.com
```