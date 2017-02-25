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
