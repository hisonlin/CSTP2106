|Command|Discription|Example|Screenshot|
|--|--|--|--|
|`ls`|List out the contents of your current working directory, including hidden file.|`ls -a`|![](img/ls%20-a.png)|
|`pwd`|Show the full path of the current working directory|`pwd`|![](img/pwd.png)|
|`cd`|Change directory to parent directory|`cd ..`|![](img/cd.png)|
|`touch`|Create an empty file in current working directory|`touch test.txt`|![](img/touch.png)|
|`cp`|Copy a file from one directory to another|`cp test.txt ..`|![](img/cp.png)|
|`rm`|Remove a file|`rm test.txt`|![](img/rm.png)|
|`mv`|Move a file to target directory|`mv test.txt ..`|![](img/mv.png)|
|`mkdir`|Make a new directory|`mkdir newDir`|![](img/mkdir.png)|
|`rmdir`|Remove a directory|`rmdir newDir`|![](img/rmdir.png)|
|`top`|Show process activity|`top`|![](img/top.png)|
|`cat`|Concatenate and print the contents of the file|`cat science.txt`|![](img/cat.png)|
|`head`|Print first x lines from a file|`head -5 science.txt`|![](img/head%20-5.png)|
|`tail`|Print last x lines from a file|`tail -5 science.txt`|![](img/tail%20-5.png)|
|`less`|View a file, press spacebar to continus press q to quit|`less science.txt`|![](img/less.png)|
|`grep`|Print the line matching a pattern. -i ignore upper or lower case; -v display those lines that do not match; -n precede each matching line with the line number; -c print only the total count of matched lines|`grep -ivc science science.txt`|![](img/grep%20-ivc.png)|
|`wc`|Count lines or words of the file|`wc -l` and `wc -w`|![](img/wc.png)|
|`tar -zxpvf`|Unzip the files|`tar -zxpvf /media/cdrom/VMwareTools-10.3..25-20206839.tar.gz`|![](img/tar-zxpvf.png)|
|`apt-get install`|Install an application|`sudo apt-get install cowsay`|![](img/install%20cowsay.png)|