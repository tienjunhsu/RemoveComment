# RemoveComment
删除C/C++代码中的注释，Remove comments in C/C++ files

删除C/C++代码中的连在一起的空行

使用Python 3，不支持Python 2

用法：
```
python RemoveComment.py input_path output_path
```
input_path output_path可以是以下组合：

*  文件路径 文件路径
*  文件路径 文件夹路径
*  文件夹路径 文件夹路径

input_path 是文件夹路径时，output_path被当做文件夹路径，
代码中将遍历搜索input_path文件夹下的所有文件，包含子文件夹，
查看文件后缀名，对代码文件执行删除注释操作后储存到output_path文件夹下；
对其它文件，仅复制到output_path文件夹下。