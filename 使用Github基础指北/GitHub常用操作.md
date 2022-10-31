# GitHub常用操作

## 将GitHub上仓库下载到本地

首先打开该仓库 复制SSH![SSH](Photos/SSH.png)

然后在电脑上右键要保存该仓库的文件夹 点击Git Bash Here

![Git Bash here](Photos/Git Bash here.png)

在Git Bash客户端输入命令行：

```
git clone SSH地址
```

这样，仓库Notes就下载到该文件夹下

## 修改仓库文件后上传到GitHub仓库

修改好后 右键仓库文件夹（Notes，不是母文件夹） 点击Git Bash Here 依次输入命令行：

```
git add .
git commit -m"说明"
git push
```

这样就上传到GitHub仓库中

