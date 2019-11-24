# 设置anaconda国内镜像

修改`C:\Users\zbxtqw\.condarc`内容如下：

```
ssl_verify: true
channels:
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
  - defaults
show_channel_urls: true
```