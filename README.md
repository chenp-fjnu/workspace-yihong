# 记录学习编程过程
学习资料：https://github.com/chenp-fjnu/KidsProgram/blob/main/%E5%88%9D%E4%B8%AD%E7%94%9F%E7%BC%96%E7%A8%8B.md

## Git操作
- 设置本地git配置
    - git config --global user.email "mail address"
    - git config --global user.name "Yihong.Chen"
- 每次结束学习执行以下两个命令，记录所有的代码变更
    - git add . //增加本地代码变更
    - git commit -m '每次提交说明变更内容' //提交代码到本地仓库

- git pull //从远程仓库获取最新代码，如果本地有没有提交的代码，无法获取，需要先执行上面两个命令
- git push //提交本地仓库的commits到远程仓库，需要github帐号登录，有的时候会超时提交不了（Timed out或者Connection was reset)，是网络问题，可以多试几次或者换个时间再试

## Python
- python demo.py //运行python脚本demo.py