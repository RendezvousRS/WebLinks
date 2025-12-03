#scoop

powershell（普通用户模式，非管理员模式打开）:

```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

Y

```
irm get.scoop.sh | iex
```

安装完毕！

检验：

```
scoop --version
```

scoop.sh
