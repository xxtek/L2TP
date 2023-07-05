# L2TP
L2TP一键安装脚本: 支持的系统：CentOS 6+ / Debian 7+ / Ubuntu 12+
Telegram: @QS00008


wget --no-check-certificate https://raw.githubusercontent.com/xxtek/L2TP/master/install.sh
chmod a+x install.sh
./install.sh



编辑ipsec配置文件

vim /etc/ipsec.conf

按i键进入编辑模式

用键盘方向键找到sha2-truncbug=no,把yes修改为no

按ESC退出编辑模式，按住shift+:输入wq退出

重启ipsec,   service ipsec restart
