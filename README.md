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
5. `uniq` stands for “unique” and filters out adjacent, duplicate lines in a file. 
To remove all duplicate files:
```
$ sort deserts.txt | uniq
```

6. `grep` stands for “global regular expression print”. It searches files for lines that match a pattern and returns the results.
grep -i enables the command to be case insensitive
```
$ grep -i Mount mountains.txt
```

Search content in directory files
```
grep -R Arctic /home/ccuser/workspace/geography
```

7. `sed`
$ sed 's/snow/rain/' forests.txt 
```
s: stands for “substitution”. it is always used when using sed for substitution.
snow: the search string, the text to find.
rain: the replacement string, the text to add in place.
In this case, sed searches forests.txt for the word “snow” and replaces it with “rain.” Importantly, the above command will only replace the first instance of “snow” on a line.
$ sed 's/snow/rain/g' forests.txt 
The above command uses the g expression, meaning “global”. 
Here sed searches forests.txt for the word “snow” and replaces it with “rain”, globally. All instances of “snow” on a line will be turned to “rain”.
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

### MYSQL
(MySQL8.0的caching_sha2_password问题)[https://blog.csdn.net/s634772208/article/details/81155068]
