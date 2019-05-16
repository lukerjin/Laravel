# Learning Materials
### Video Courses
[Laracasts](https://laracasts.com)

### Tools
[Oh My Zsh](https://ohmyz.sh/)


### Set up Apache and PHP7 (Windows)
1. Save Thread Safe (TS) PHP7 extract files on C:/PHP
2. Add environment variable path for PHP
3. Install Apache on C:/Apach
4. Add AddType and Modul for PHP, php7apache2_4.dll can be find in php folder
```
	AddType  application/x-httpd-php         .php
	AddType  application/x-httpd-php-source  .phps

	LoadModule php7_module modules/php7apache2_4.dll
```
5. cd Apache/bin/
6. httpd

### PHP Programming Skills
```
function getArray() {
    return array(1, 2, 3);
}

$secondElement = getArray()[1];
```
