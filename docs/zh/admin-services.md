# 服务启停

使用由Websoft9提供的 Jetty 部署方案，可能需要用到的服务如下：

## Jetty

```shell
sudo systemctl start jetty-server
sudo systemctl stop jetty-server
sudo systemctl restart jetty-server
sudo systemctl status jetty-server

# you can use this debug mode if Jetty service can't run
jetty-server console
```

### MySQL

```shell
sudo systemctl start mysql
sudo systemctl stop mysql
sudo systemctl restart mysql
sudo systemctl status mysql
```

### Redis

```shell
systemctl start redis
systemctl stop redis
systemctl restart redis
systemctl status redis
```