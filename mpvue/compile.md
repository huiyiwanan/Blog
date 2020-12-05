![image-20201205115110330](C:\Users\hujiehui\AppData\Roaming\Typora\typora-user-images\image-20201205115110330.png)

```
<import src="/https192.168.10.62svnhw4webf-branchesf-hw4web-分支-（1201昆山项目小程序需求）/src/pages/demo/demo.vue.wxml" />
```

mpvue 编译出来的wxml文件 找不到src，原因是用了中文名以及中文字符，把最外层文件夹名称改成纯英文就ok了

