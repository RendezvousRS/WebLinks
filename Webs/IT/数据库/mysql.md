# codes

>- 安装在windows系统、docker环境下
>- mysql在wsl ubuntu下也可以安装，但不如docker下好用

### linux环境

```
docker run -d \
  --name mysql \
  -e MYSQL_ROOT_PASSWORD=123456 \
  -p 3306:3306 \
  mysql:8.0
```

### windows powershell环境

```
docker run -d `
  --name mysql `
  -e MYSQL_ROOT_PASSWORD=123456 `
  -p 3306:3306 `
  mysql:8.0
```

### windows cmd环境

```
docker run -d --name mysql -e MYSQL_ROOT_PASSWORD=123456 -p 3306:3306 mysql:8.0
```
