# the show modle of **intantPlantform Plan**

生成带有目录的Markdown格式文档
https://blog.csdn.net/uxyheaven/article/details/49253757 

## 第一步 使用一个基于ruby的转换工具将写好的文档进行转换

https://github.com/i5ting/tocmd.gem

```
// 安装
sudo gem install tocmd

// 指定单个文件
sudo tocmd_local -f xx.md

// 指定目录
sudo tocmd -d .
```