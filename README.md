### 安装font-spider-plus

```
npm i font-spider-plus -g
```

### 项目目录执行命令：

```
fsp local index/font.html
```

### 使用font-spider-plus对中文字体进行压缩，注意以下几点：

1、压缩的字体必须为ttf格式

2、font-spider-plus压缩时是以执行font.html中的中文进行压缩的，也就是只包含font.html中的中文，项目中的font.html默认包含6000常用中文

3、每次执行完需要重新关闭命令行窗口，否则会提示字体被占用，无法操作

### 目录说明

before_compression：为压缩前的字体目录，备份用

font：压缩完的字体，压缩前需要把字体放入该目录，

​    .font-spider：执行fsp local index/font.html命令后备份字体的目录

index：转换和测试的html