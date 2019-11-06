#window上,huanong前后端分离项目，参考慕课网的对接真实数据 从0开发前后端分离企业级上线项目

##前端开发环境搭建
1.语言环境：jQuery、Webpack1.15.0、Nodejs6.12.3、git
2.开发工具：Sublime
3.浏览器：Chrome
4.代理工具：Charles/Fiddler
##node.js、npm的介绍和安装
1、nodejs简介
```
定义：js的服务器端运行环境，可以类比成PHP、python
用途：构建工具webpack的环境依赖
特点：单线程、异步编程
应用场景：低运算、高I/O

```
2、Nodejs的包管理工具---npm
3、nodejs安装:官网地址：https://nodejs.org/
```
Mac:node-vxxx.pkg
Windows:node-vxxx.msi
Linux:node-vxxx-linux-x64.tar.gz
```
4、window上安装
```
从官网下载在你指定的位置，然后点安装，一直点next就行了，默认是全局安装
```
##git简介
1、介绍：git是一款免费、开源分页式版本控制系统，用于敏捷高效地处理任何或大或小的项目
2、git常用命令
```git
git init :用来初始化项目
git commit -am '注释' ：用于提交代码
git checkout branch :用于切换分支
git merge:做分支的合并
git pull /git push :做代码的拉取、提交
```
3.git配置 --.gitConfig,下面是我的配置很简单
```git
[user]
    name = huano
    email = xxxxx@qq.com
[core]
    autocrlf = false
    quotepath = off
    ignorecase = false
[gui]
    encoding = utf-8


如果你用的是全局安装，即在cmd里输入git version ，会输出版本号
.gitcofig文件在 C:\user\用户名\.gitconfig  
打开这个文件，就可以配置了

用命令行配置也是可以的
```


4、window上安装
```
在官网上下载到指定位置，点击安装，一直点Next，就可以了
安装完，你在任意位置用鼠标右击就可以看到Git Bash
```
##Sublime
1、优点
```
功能设计合理，支持多光标操作
轻量级，运行速度快，运行流畅
界面简洁美观，有利于集中注意力
扩展性良好
```
2、sublime常用设置
```
Sublime Text->Preferences->Setting-User

{
    "color_scheme": "Packages/Theme - Brogrammer/brogrammer.tmTheme",
    "font_size": 24,
    "ignored_packages":
    
    [
        "Markdown",
        "Vintage"
    ],
    "theme": "Brogrammer.sublime-theme",
    "update_check":false,
}
以上是我的设置，可以自行增加
```
3、常用快捷键
```
    快捷键                     作用
    cmd+shift+d                复制行
    cmd+shift+k                删除行
    cmd+;                      注释
    cmd+w                      关闭当前标签
    cmd+n                      打开新标签
    cmd+shift+t                恢复关闭的标签
    cmd+d                      查找并选择
    cmd+f                      当前页查找
    cmd+shift+f                在文件夹中查找
```
##http代理的原理
```
非代理   输入b.com  -------------->b.com 

代理     输入b.com  -->代理服务器-->b.com 
                          |劫持
                        a.com 
```
##Charles or Fiddler
```
   Charles                  Fiddler

   Mac系统                   window系统
   依赖java                  依赖.net
   收费                      免费

```
#项目初始化
##git仓库建立
```
git 项目的建立
git权限配置
gitignore的配置
```



