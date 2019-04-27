   ### Github代理服务器设置，解决克隆访问速度慢问题
###### 前提：需要有自己的VPN代理（注：最后面1087换成自己SS代理端口）

 ##### 设置代理：
```bash
git config --global http.https://github.com.proxy http://127.0.0.1:1087
git config --global https.https://github.com.proxy http://127.0.0.1:1087
```

 ##### 查看代理：
```bash
git config --global http.https://github.com.proxy
git config --global https.https://github.com.proxy
```

 ##### 取消代理：
```bash
git config --global --unset http.https://github.com.proxy http://127.0.0.1:1087
git config --global --unset https.https://github.com.proxy http://127.0.0.1:1087
```
