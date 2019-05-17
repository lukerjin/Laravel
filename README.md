# Learning Materials
### Video Courses
[Laracasts](https://laracasts.com)

### Tools
[Oh My Zsh](https://ohmyz.sh/)  
[SequelPro](https://www.sequelpro.com/)

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

### CML Notes
1. `PWD` pwd stands for “print working directory
```
$ pwd
/home/user/workspace
```  
2. `touch` command creates a new file inside the working directory.
```
touch keyboard.txt
```
3. Rename file
```
mv batman.txt spiderman.txt
```  
4. Remove directories
```
rm -r removes directories
```

### PHP Programming Skills
1. Array dereferencing
```
function getArray() {
    return array(1, 2, 3);
}

$secondElement = getArray()[1];
```

2. Variable

```
$b = "b";
echo "a" . "b"; // ab
echo "a" . $b;  // ab
echo "a $b c";  // a b c
echo "a ${b}c"; // abc
```  
```  
$full_name = "a";
$full_name .= " b";
echo $full_name; // Prints: ab
```  
