## [处理TortoiseGit一直弹出密码框的方法 -输入git@XXXX.com的密码](https://blog.csdn.net/rentingting0312/article/details/93055363?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.control&dist_request_id=54f875ac-0721-4580-8b6a-e1bb157290f5&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.control)
1. 开始处搜索TortoiseGit文件夹，找到其中的“PuTTYgen”文件
2. 运行之后在弹出的窗口中点击下方的“Generate”按钮，这样就会自动生成一个SSH-Key。另外：在生成key的时候鼠标要一直在进度条上滑动，只有这样进度条才会移动
3. 生成之后使用下方的“Save private key”按钮将这个密匙保存起来，保存的时候请自己设置保存的位置，然后请记住自己保存的文件夹
4. 接着将生成的key复制粘贴到Gitlab SSH-Keys区域中
5. 完成密匙的生成之后接着再次进入到开始菜单中找到TortoiseGit文件夹，将其中的“Pageant”打开 接着点击下方的“Add Key”按钮，然后在弹出的文件夹界面中找到刚刚保存的密匙即可！

of course 也可以通过 PuTTYgen的"Load" 方法
