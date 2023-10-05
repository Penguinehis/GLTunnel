# GLTunnel

```sh
apt update && apt upgrade -y && apt install apache2 php7.2 mariadb-server -y && service apache2 restart && service mysql restart && apt install phpmyadmin php-curl php-mysql -y && service apache2 restart
```


```sh
CREATE USER 'painelgl'@'localhost' IDENTIFIED BY 'SUASENHA';
GRANT ALL PRIVILEGES ON *.* TO 'painelgl'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
```
