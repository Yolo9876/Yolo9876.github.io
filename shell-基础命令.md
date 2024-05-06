```shell
#!/bin/sh
 
# 指定要检查的文件或目录
FILE_OR_DIR="/path/to/your/fileordir"
 
# 判断文件或目录是否存在
if [ -e "$FILE_OR_DIR" ]; then
    echo "文件或目录存在"
else
    echo "文件或目录不存在"
fi
```
