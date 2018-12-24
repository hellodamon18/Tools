# jupyter notebook rise 制作

[TOC]



## 一、安装环境

### 1.1 [jupyter官网](https://jupyter.org/)

### 1.2 [rise](https://github.com/damianavila/RISE)

### 1.3 安装方式

    ​```python
    pip install jupyter		# 安装jupyter
    pip insatll RISE		# 安装rise
    jupyter-nbextension install rise --py --sys-prefix		# install the JS and CSS in the proper places
    jupyter-nbextension enable rise --py --sys-prefix
    ​```

## 二、操作方式

### 2.1 创建本地notebook文件夹

``` cmd
cd D:
mkdir notebook
cd notebook			# 创建本地notebook文件夹
jupyter notebook	# 切换到本地项目根目录下执行
```

### 2.2 创建文件

*   空notebook库

![notebook库](.\1.PNG)

*   新建文件

    ![new file](.\2.PNG)

*   插入

  >   *   可选插入代码或者markdown标记文本
  >   *   ctrl + enter实现代码运行和markdown文本显示

  ![插入](.\3.PNG)

  ![运行](.\4.PNG)

### 2.3 ppt放映
> 可选择每页显示的主题

![ppt](.\5.PNG)

![ppt](.\6.PNG)

> ppt放映时，可以直接编辑代码，ctrl+enter进行编译显示

![ppt](.\7.PNG)