# hugo blog use:

- [hugo blog use:](#hugo-blog-use)
  - [1.下载hugo.exe 执行](#1下载hugoexe-执行)
  - [2.git初始化](#2git初始化)
  - [3.进入themes下载主题](#3进入themes下载主题)
  - [4.启动预览hugo](#4启动预览hugo)
  - [5.部署文件整理](#5部署文件整理)


## 1.下载hugo.exe 执行
hugo new site zld126126.github.io
## 2.git初始化
git init
## 3.进入themes下载主题
cd themes
git submodule add https://github.com/dillonzq/LoveIt themes/LoveIt
## 4.启动预览hugo
hugo server -v -D
## 5.部署文件整理
hugo -D