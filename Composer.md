# Composer

### 安装Composer
* 首先安装PHP，配置环境变量
* 下载composer.phar文件

    `
     php -r "copy('https://install.phpcomposer.com/installer', 'composer-setup.php');" 
     php composer-setup.php	
     php -r "unlink('composer-setup.php');"
    
    `
* 将composer.phar移动至PHP安装目录bin下，并在该目录下新建composer.bat文件


    `
    	@php "%~dp0composer.phar" %*
    `
* 安装成功，查看版本号。

    `
    	composer --version
    `
* 更新composer版本

    `
    	composer selfupdate
    `

### 使用国内镜像

* 全局配置

    `
    composer config -g repo.packagist composer https://packagist.phpcomposer.com

    // 执行全局安装
    composer global require
    // 修改php.ini文件中的include_path为全局composer vendor，在项目中可以使用require_once 'autoload.php'进行类库注册
    `

* 局部配置

    `
    composer config repo.packagist composer https://packagist.phpcomposer.com
    // 执行局部安装
    composer require
    `


