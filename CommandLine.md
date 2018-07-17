# 查找与替换
1. 替换文件中的指定字符串:
+ 示例：把当前目录下所有java文件中的old替换成new \
perl -p -i -e "s/old/new/g" ./**/*.java

2. 用python快速跑一个http服务器显示目录以及文件:</br>
python -m http.server 80
