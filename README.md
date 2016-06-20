<<<<<<< HEAD
#国内环境下安装使用yeoman (yo bootstrap gulp sass)安装
------------------------------------------

**Step1**、安装NodeJs
=======
# 国内环境下安装使用yeoman (yo bootstrap gulp sass)安装
------------------------------------------

**Step1**、安装NodeJs

 1. 从NodeJs官网下载安装包 http://nodejs.org/ 直接进行安装
 2. 修改npm 镜像源为 **淘宝镜像** 
 
    1.通过config命令

    npm config set registry https://registry.npm.taobao.org 

    npm info underscore（如果上面配置正确这个命令会有字符串response）
    
    2.命令行指定：
    
    npm --registry https://registry.npm.taobao.org info underscore
    
    3.编辑 .npmrc 加入下面内容（在用户主目录下 ）：
    
    registry = http://registry.npm.taobao.org

**Step2**、npm安装 yo gulp bower 

    npm install -g yo gulp 
    
    npm install -g generator-
    
    
**Step3**、使用yo

    1. cd 到项目目录 执行
    
    npm init
    
    yo webapp
    
    2. 执行gulp serve 启动gulp
    
    如果出错 执行 
    
    npm install -save-dev node-sass
    
    npm install -save-dev gulp-sass
    
>>>>>>> origin/master

 1. 从NodeJs官网下载安装包 http://nodejs.org/ 直接进行安装
 2. 修改npm 镜像源为 **淘宝镜像** 
    1.通过config命令
    npm config set registry https://registry.npm.taobao.org 
    npm info underscore（如果上面配置正确这个命令会有字符串response）
    2. 命令行指定：
    npm --registry https://registry.npm.taobao.org info underscore
    3.编辑 .npmrc 加入下面内容（在用户主目录下 ）：
    registry = http://registry.npm.taobao.org

**Step2**、npm安装 yo gulp bower 
    npm install -g yo gulp bower
    npm install -g generator-webapp
    
**Step3**、使用yo
    1. cd 到项目目录 执行
    npm init
    yo webapp
    2. 执行gulp serve 启动gulp
    如果出错 执行 
    npm install -save-dev node-sass
    npm install -save-dev gulp-sass