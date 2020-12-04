## github 关联account email

1. git config --global user.name "xx"
2. git config --global user.email "xx@xx.com"

## github ssh

1. 配置ssh
      1. git clone SSH-link
      2. 若无公钥 - 则下一步
         1. ssh-keygen -t rsa 连续回车三次  
         2. 到指定的目录下 复制 .pub文件内容至github ssh配置中
2. 再次clone ssh远程仓库-link

