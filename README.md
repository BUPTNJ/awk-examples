# awk-examples
using awk to extract information from text like html to make a csv file.
使用linux的awk命令结合正则表达式从文本文件（如html）中提取想要的信息的一个例子，生成csv格式的文件。

# warning
some old versions may not support match(a,b,c), you can install gawk to replace it.
有的系统中所带的awk版本可能不支持match的三个参数（只支持两个），可以安装gawk来替代。

# how to use?
cat 180801.html | gawk -f cmd.txt >180801.csv
