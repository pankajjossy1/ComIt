ComIt
=========

ComIt (Compile It) is a online compiler made by using [HackerEarthApi's].

  - Just simply run the code using your Linux Terminal.
  - No need to install any package.




Installation
--------------

Linux :
___
```sh
git clone https://github.com/iMshyam/ComIt.git
cd ComIt
python config.py
exit
Ctrl+Alt+t(restart the terminal)
```
Windows:
___
install [Python]

if cmd doesn't understand python then you need to set environment variable 'python'

For setting environment variable open Windows Power-Shell and paste : [Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python27", "User")

now download [this]
```sh
go to downloads and right click on "ComIt-master" and click on extract here
open cmd as Admin
paste it in cmd : cd %userprofile%\Downloads\ComIt-master\
then run : python configWindows.py
click on 'YES' when asked for adding Registry
restart cmd(no need to open as Admin)

```

Usage
----
(same for both windows and linux)
```sh
comit 'Name of file containing code with location' 'Input File Name with location'
#Location is required if the file is in another folder
#No need to provide input file name if there is no input
```
for exapmle :
(in this example i'm writing all permutations of 12 and 123 in increasing order.) 
```sh
Ctrl+Alt+t
cd ComIt
comit test.py input.text
# or location of test.py and input.txt
```

Version
----

2.0




Language Support
------
all supportes languages till now are:

* C
* C++
* Python
* Java 
* Objective-C 
* Perl 
* PHP 
* ruby
* C#
* Haskell 
* Clojure
 


Tech
-----------

ComIt uses :

* python and
* HackerEarth Api's

    to work properly.
    
License
----
[Licensed] under -

The MIT License (MIT)

**Free Software**

[HackerEarthApi's]:http://developer.hackerearth.com/
[Python]:https://www.python.org/ftp/python/2.7.8/python-2.7.8.msi
[this]:https://github.com/iMshyam/ComIt/archive/master.zip
[Licensed]:https://github.com/iMshyam/ComIt/blob/master/LICENSE
