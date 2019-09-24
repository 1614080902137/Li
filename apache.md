# 关于运行php
## 配置php
* /config/httpd.conf
```
  #LoadModule vhost_alias_module modules/mod_vhost_alias.so
  #LoadModule watchdog_module modules/mod_watchdog.so
  #LoadModule xml2enc_module modules/mod_xml2enc.so

  LoadModule php7_module "E:/php-7.3.9/php7apache2_4.dll"

  AddType application/x-httpd-php .php
```
```
  <IfModule dir_module>
      DirectoryIndex index.html index.php
  </IfModule>
```
