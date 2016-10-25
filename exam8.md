##8. 描述在linxu系统上安装nodejs具体步骤
nodejs安装包解压后，在bin文件夹中已经存在node以及npm，如果你进入到对应文件的中执行命令行一点问题都没有，不过不是全局的，所以将这个设置为全局就好了。
　cd node-v0.10.28-linux-x64/bin
　　ls
　　./node -v
然后设置全局：
　　ln -s /home/kun/mysofltware/node-v0.10.28-linux-x64/bin/node /usr/local/bin/node
　　ln -s /home/kun/mysofltware/node-v0.10.28-linux-x64/bin/npm /usr/local/bin/npm
　　这里/home/kun/mysofltware/设置路径
