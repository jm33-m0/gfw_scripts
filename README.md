# gfw-script
## 适应症：GFW

## Disclaimer / 声明

- **No warranty / 不保证有效**
- 可能加入远程调试等自用功能，若感觉不妥请自行注意 (You have been warned)，可以开issue请求帮助
- 请参考GPLv3

## 功能说明

- `ss_install.sh`

    这是一个在Linux服务器上自动安装Shadowsocks-Plus的脚本，复制粘贴
    `wget https://raw.githubusercontent.com/jm33-m0/gfw_scripts/master/ss_install.sh && bash ss_install.sh`，根据提示操作

- `ss_add.sh`

    用于添加SS用户，可以交互式输入配置，也可以用于一键批量添加，
    `./ss_add.sh -i`会使用交互模式，`./ss_add.sh <user> <port> <password>`是一键模式

- `hosts.sh`

    安装并实现自动更新hosts文件，来自于[racaljk/hosts](https://raw.githubusercontent.com/racaljk/hosts/master/hosts "raw file")

![./hosts.sh](https://jm33.me/img/hosts-sh.png)

![ping](https://jm33.me/img/hosts.png)

- `conn_chk.sh`

    检测国内外网络连接

- `pac-gfwlist`

    PAC文件，来自[Cloverr0/pac-gfwlist](https://github.com/Cloverr0/pac-gfwlist)

- `paste.sh`

    粘贴文本到[Pastebin](http://pastebin.com)

- `shadow.sh`

    安装Shadowsocks插件，请参考[jm33_m0 - 极路由4使用Shadowsocks插件（含web配置面板）](https://jm33.me/ji-lu-you-4shi-yong-shadowsockscha-jian-han-webpei-zhi-mian-ban.html)

    ![](https://jm33.me/img/ss1.png)

    ![](https://jm33.me/img/ss3.png)

- `rm.sh`

    清除远程调试功能
