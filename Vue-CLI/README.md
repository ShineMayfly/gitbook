# Vue-CLI

### 1、使用vue-cli + webpack搭建vue开发环境



#### ①、环境要求

- [node](https://nodejs.org/zh-cn/)
- [webpack](https://www.webpackjs.com/)
- [vue-cli](https://cli.vuejs.org/zh/)

#### ②、安装环境

 node:

到 [node.js官网](https://nodejs.org/zh-cn/)下载最新的安装包安装

webpack:

```bash
$ npm install webpack
```

vue-cli:

```bash
$ npm install vue-cli -g
```

#### ③、创建vue项目

###### 创建项目

```bash
$ vue init webpack my-app(项目名)
```

###### 初始化项目

1、项目名称

![项目名称](image/1.jpg)

不输入项目名称会默认刚刚输入的项目名，即括号内的名称

2、项目描述

![项目描述](image/2.jpg)

不输入会默认括号内的描述

3、项目作者

![项目作者](image/3.jpg)

不输入默认

4、vue-router

![vue-router](image/4.jpg)

是否使用vue-router，这里选择Y使用

5、ESLint

![ESLint](image/5.jpg)

是否使用ESLint,这里选择Y使用（可以选择不使用，之后再配置）

6、unit 和 e2e tests 

![unit&e2e tests](image/6.jpg)

unit和e2e tests 这里选n不使用

7、安装依赖包

![download package](image/7.jpg)

可以选择npm或yarn,也选择选no,之后自己安装

###### 运行项目

8、运行

先安装依赖包，如果之前已经安装好依赖包,现在可以直接使用命令行进入项目文件夹

```bash
$ cd my-app
$ npm run dev
```

![run](image/8.png)

当出现上面提示时，此时可以打开浏览器输入http://localhost:8080 查看项目

#### ④、简单配置

###### 1、修改favicon

将你的favicon.ico文件放到项目的static文件夹下

在index.html head里增加

```html
<link rel="shortcut icon" href="static/favicon.ico">
```

刷新网页，此时你的项目的favicon已经变成你的icon了。



###### 2、搭建mock server

需要用到[mock.js](http://mockjs.com/) 和 [axios](../Axios),可以到官网学习

安装依赖

```bash
$ npm install axios --save
$ npm install mockjs --save-dev
```

搭建web server





