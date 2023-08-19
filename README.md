# code-server-docker-deploy
vscode-server docker部署配置

### 介绍
> 在linuxserver/code-server基础上，创建了两个镜像brownant/code-server和brownant/code-server-x86。更方便拉取，不过不方便更新。
>
> 目前主要是简单增加了一层node的安装，用于js的调试和开发。

### 工程说明
```shell
amd64 文件夹
linux x86架构可以使用

arm 文件夹
linux arm架构可以使用

arm/amd64 文件夹下有data文件夹，里面有node压缩包和一个安装开发工具脚本。
data文件夹内容会复制到/opt目录下。

```
