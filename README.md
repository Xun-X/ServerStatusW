# ServerStatusW
Windows上显示一个半透明的飘浮窗，实时监看服务器状态(ServerStatus探针)

##### 效果展示：
![](https://raw.githubusercontent.com/Xun-X/ServerStatusW/main/Screenshots3.png)

##### 程序说明：
本程序是读取[ServerStatus探针]服务端WEB数据用于飘浮窗显示服务器状态，所以服务器需要安装[ServerStatus探针]

##### 设置简单说明：
例：[ServerStatus探针]访问地址是：```http://tanzhen.hostname.com:808```
如图：
![](https://raw.githubusercontent.com/Xun-X/ServerStatusW/main/Screenshots1.png)

##### 参考如下设置即可：
![](https://raw.githubusercontent.com/Xun-X/ServerStatusW/main/Screenshots2.png)
特别说明：[设备名称配置]填入的名称与WEB上对应的[节点名]相同即可
 
#### ServerStatus探针 服务端 安装：
```
wget -N --no-check-certificate https://raw.githubusercontent.com/iiiiiii1/doubi/master/caddy_install.sh && chmod +x caddy_install.sh && bash caddy_install.sh
wget https://raw.githubusercontent.com/cokemine/ServerStatus-Hotaru/master/status.sh
bash status.sh s
```

#### ServerStatus探针 客户端 安装：
```
wget -N --no-check-certificate https://raw.githubusercontent.com/iiiiiii1/doubi/master/caddy_install.sh && chmod +x caddy_install.sh && bash caddy_install.sh
wget https://raw.githubusercontent.com/cokemine/ServerStatus-Hotaru/master/status.sh
bash status.sh c
```
