存放订阅 telegrambot

安装教程

先去botfather获取bot token，然后在vps内使用一下命令安装bot

git clone https://github.com/xuanyi0121/Sub_Manger

Debian | Ubuntu:

apt-get upgrade -y 
apt install -y python3 python3-pip 
pip3 install -r requirements.txt

CentOS

yum update -y
yun install -y python3 python3-pip
pip3 install -r requirements.txt

运行方式

直接使用Python命令调用Bot即可

python3 main.py

建议使用screen、systemd、PM2等工具将Bot挂在后台运行。

安装依赖

pip3 uninstall telebot
pip3 uninstall PyTelegramBotAPI
pip3 install pyTelegramBotAPI
pip3 install --upgrade pyTelegramBotAPI

pip install pyTelegramBotAPI

作者是https://github.com/hero81/Sub_Manger
