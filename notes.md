# 注意github for windows 和 git for windows 虽然都有git shell，但有一点区别
    前者安装的时候就自动生成了known_hosts文件，也就是github的公钥；
    后者是没有的，必须使用命令ssh-keyscan -t rsa github.com > ~/.ssh/known_hosts手动添加
