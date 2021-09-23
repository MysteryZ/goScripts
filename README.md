# goScripts
一些工作中使用的go脚本

## backup.go

递归拷贝源目录下的某种类型文件到另一个目录，并且保持目录结构。

工作需要将一个大型java项目源码下的pom.xml文件拷贝出来，并且保持pom文件的目录结构。

最近在学习go语言，参考了一些别人的代码编写了这个脚本。

```
Usage of backup:
  -d string
        the dest path to copy from (default "bb")
  -f string
        the filename to copy  (default "ff")
  -s string
        the source path to copy from (default "aa")
```



