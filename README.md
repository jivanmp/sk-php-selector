# Se usa como base y referencia
https://github.com/Skamasle/sk-php-selector

# sk-php-selector
PHP selector for centos 6/7 

# RUN AT YOUR OWN RISK

This install php 5.4, 5.5, 5.6, 7.0, 7.1, 7.2, 7.3, 7.4, 8.0 and 8.1 in your centos 6 and centos 7

**Use sk-php-selector2.sh, in this you can select what php version install
sk-php-selector3.sh is same as sk-php-selector2.sh but with simplified code, now in testing **

bash sk-php-selector3.sh php72

bash sk-php-selector3.sh php80

bash sk-php-selector3.sh php81

# Or install multiple version

bash sk-php-selector3.sh php56 php71 php 8.1

# or install all

bash sk-php-selector3.sh all

This works fine, the configuration of php need some work so try firts in test enviroment

------------

This can break phpmyadmin, in this case you need delete some mod_php files in /etc/httpd/conf.d/ you can move out all php??.conf just leave php.conf ( not delete maybe you need restore it )

This is aleatory and need more debugin, not always was broken so I cant say you exactly, but the solution is wasy
