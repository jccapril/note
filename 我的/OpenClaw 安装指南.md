# 安装命令 PowerShell （管理员打开）
----
1. 安装git https://git-scm.com/download/win

2. 放开安全策略
`Set-ExecutionPolicy -Scope CurrentUser RemoteSigned`  选择：Y

3. 一键安装命令, 安装过程中会发生错误，常见错误是没有安装git和npm的网络问题，修复好之后，重新执行
`iwr -useb https://openclaw.ai/install.ps1 | iex`

4. 如没有国外环境，需要设置设置国内镜像源：
`npm config set registry https://registry.npmmirror.com`