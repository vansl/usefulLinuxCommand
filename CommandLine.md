# 查找与替换
1. 替换文件中的指定字符串：
+ 示例：把当前目录下所有java文件中的old替换成new \
perl -p -i -e "s/old/new/g" ./**/*.java
