# tag
## grep
- egrep  '正则表达式' file (grep -E)
-   -n print  linenum

## sed
- p print
- d delete
- s replace
- q quit
-  -i 回写文件
-  -n 打印处理行
-  s g全部替换
### 查找
- n1,n2
- /正则表达式/

### 通用 
- sed -i '/root/{s/uu/hhh/g;p;q}' file
- sed -i '3，5{s/uu/hhh/g;p;q}' file


###php

- ./ext_skel –extname=yourext
- config.m4

> dnl PHP_ARG_WITH(myext, for myext support,
dnl Make sure that the comment is aligned:
dnl [  --with-myext             Include myext support])

> PHP_ARG_WITH(myext, for myext support,
[  --with-myext             Include myext support])

- ext目录下依次执行phpize、./configure 、make、make install。然后修改php.ini加入extension={your ext.so}
