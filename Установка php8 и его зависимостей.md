```shell
sudo apt install -y php8.0-{mysql,cli,common,snmp,ldap,curl,mbstring,zip,xml,sqlite} -y
```

## Добавление рабочих в России зеркал: PHP для Debian12
  
в **/etc/apt/sources.list.d/php.list** комментируем все и добавляем в конец  
  
Если Debian 11 (Bullseye)  

```shell
deb https://ftp.mpi-inf.mpg.de/mirrors/linux/mirror/deb.sury.org/repositories/php/ bullseye main
```
  
Если Debian 12 (Bookworm)  

```shell
deb https://ftp.mpi-inf.mpg.de/mirrors/linux/mirror/deb.sury.org/repositories/php/ bookworm main
```
