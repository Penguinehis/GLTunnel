# GLTunnel

```sh
apt update && apt upgrade -y && apt install apache2 php7.2 mariadb-server -y && service apache2 restart && service mysql restart && apt install phpmyadmin php-curl php-mysql -y && service apache2 restart
```


```sh
CREATE USER 'painelgl'@'localhost' IDENTIFIED BY 'SUASENHA';
GRANT ALL PRIVILEGES ON *.* TO 'painelgl'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
```


```sh
cd /var/www/html && apt install unzip -y && wget https://github.com/Penguinehis/GLTunnel/raw/main/htdocs.zip && unzip htdocs.zip && rm index.html htdocs.zip
```

```sh
sed -i 's/2d064f28588136d4bed6fe5c05ca6d90/SUAKEYIMGBB/g' /var/www/html/app_config.php
```
