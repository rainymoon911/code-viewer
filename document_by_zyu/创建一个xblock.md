xblock创建
========
[参考网站](http://xblock.readthedocs.org/en/latest/getting_started.html)




安装XBlock：
=======
git clone https://github.com/edx/XBlock.git

加载环境变量
source /edx/app/edxapp/edxapp_env

进入目录进行安装
sudo pip install -r requirements.txt

下载xblock-sdk,方法同XBlock安装

使用XBlock-SDK进行XBlock的开发

创建目录edxwork用于新的XBlock

$ cd ~

$ mkdir edxwork

$ cd edxwork

$ sudo /path/to/xblock-sdk/script/startnew.py

startnew.py脚本需要一个目录名以及一个类名参数，
此处使用myxblock,MyXBlock
创建完成后在edxwork目录下即生成myxblock工作目录

以后的代码编写工作基本都在/myxblock/myxblock.py文件中完成
安装命令：pip install -e myxblock

代码编写：(待续)
