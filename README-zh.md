# mcd
<a href="https://github.com/Ordneri/mcd/blob/main/README.md">English</a>
&nbsp;&nbsp;| &nbsp;&nbsp;
中文

## 关于

`mcd` 是linux脚本，用来创建目录和进入到该目录用的。

## 安装方式

在BASH里面执行:
```bash
curl -sSL -o mcd.temp https://raw.githubusercontent.com/Ordneri/mcd/main/mcd && mv mcd.temp $PREFIX/bin/mcd
```

## 用法


这样用-> ". mcd NewDirName" ，把NewDirName换成你想创建的文件夹名称就行。
**要注意的是，命令开头是点和空格，一定要加的哦（你不会想试一下不加会发生什么吧）。**
```
. mcd NewDirName
```

## 卸载


在BASH里面执行:
```bash
rm -f $PREFIX/bin/mcd
```
实际上就是帮你删一个文件

## Note


为我只在Termux上面测试过，嘿嘿嘿。
