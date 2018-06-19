# gxc-python
python3爬虫学习记录

1.下载Anaconda安装python环境
https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/Anaconda3-5.2.0-Windows-x86_64.exe
验证
python -v
pip --version
更换pip国内源
创建文件夹C:User\administrotor\pip、复制pip.ini到pip文件夹中

2.pip安装的第三方库
pip install requests
pip install selenium

安装自动化测试工具
http://npm.taobao.org/mirrors/chromedriver/
https://github.com/mozilla/geckodriver/releases
http://phantomjs.org/download.html
https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-2.1.1-windows.zip
安装ChromeDriver GeckoDriver PhantomJS
运行测试脚本

pip install aiohttp
pip install lxml
pip install pyquery
运行测试脚本

pip install beautifulsoup4
运行测试脚本

安装图片验证码解析库
http://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-setup-4.00.00dev.exe
https://download.lfd.uci.edu/pythonlibs/j1ulh5xc/Twisted-18.4.0-cp36-cp36m-win_amd64.whl
pip install tesserocr pillow

ubuntu安装Mysql Mongodb Redis

apt install mysql
修改/etc/mysql/mysql.conf.d/mysqld.cnf
注释bind-address=127.0.0.1


apt install mongodb
mongod --port 27017 --dbpath /data/db
mongo --port 27017
use admin
db.createUser({user:'admin',pwd:'admin123',roles:[{role:'root',db:'admin'}]})

安装db连接工具
pip install pymysql
pip install pymongo
pip install redis
验证安装
import pymysql
pymysql.VERSION

import pymongo
pymongo.version

import redis
redis.VERSION

安装ruby
https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.5.1-1/rubyinstaller-devkit-2.5.1-1-x64.exe
gem install redis-dump
验证安装 
redis-dump
redis-load

安装pyspiderp爬虫框架
pip install pyspider

运行pyspider命令
pyspider all