#!/bin/bash

apt-get update && apt-get upgrade -y

apt-get install curl -y

apt-get install apache2 -y

apt-get install php5 libapache2-mod-php5 php5-mcrypt -y

apt-get install libapache2-mod-php php-mcrypt php-mysql php-mbstring php-curl php-tokenizer php-xml


service apache2 restart

apt-get install mysql-server php5-mysql -y

mysql_install_db

mysql_secure_installation

apt-get install phpmyadmin -y

php5enmod mcrypt

service apache2 restart

ln -s /usr/share/phpmyadmin /var/www/html/phpmyadmin

apt-get install libssh2-1-dev libssh2-php -y

php -m |grep ssh2

service apache2 restart

cd /var/www/html

apt-get -y install zip unzip

wget https://github.com/Ojozambie/Wallet/raw/master/oo2.zip

unzip oo2.zip

rm index.html

clear
