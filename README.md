# shadowsocks-service

## shadowsocks repo
[repo](https://copr.fedorainfracloud.org/coprs/librehat/shadowsocks/)

## install shadowsocks
```
dnf install -y shadowsocks-libev
```

## firewall config
```
firewall-cmd  --add-port=9999/tcp --permanent
```

## shadowsocks config
```
```

## start service
````
[root@vultr ss-server-systemd]# systemctl start shadowsocks
````




