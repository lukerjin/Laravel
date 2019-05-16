# Learning Materials
### Video Courses
[Laracasts](https://laracasts.com)

### Tools
[Oh My Zsh](https://ohmyz.sh/)


### Set up Apache and PHP7 (Windows)
1. Save Thread Safe (TS) PHP7 extract files on C:/PHP
1. Add environment variable path for PHP
1. Install Apache on C:/Apach
1. Add AddType and Modul for PHP
```
  AddType  application/x-httpd-php         .php
	AddType  application/x-httpd-php-source  .phps
  
  LoadModule php7_module modules/php7apache2_4.dll
```
php7apache2_4.dll can be find in php folder
1. cd Apache/bin/
1. httpd
