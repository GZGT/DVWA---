# DVWA---
本次白盒测试主要针对DVWA的11个漏洞，对DVWA各个安全等级的源代码进行审计，寻找漏洞签名，并且对漏洞进行测试。

DVWA源码：
=>最新的：https://github.com/digininja/DVWA
=>本教程使用旧的版本：https://pan.baidu.com/s/1yplrbSstdMTd6En1xi08PQ?pwd=6666 

搭建：
=>小皮面板：www.xp.cn
=>XAMPP：https://www.apachefriends.org/download.html

新安装的DVWA需要把config文件夹下的config.inc.php.dist文件改为config.inc.php。
然后在config.inc.php配置文件里把db_password改为数据库密码。

来到php配置检查页面，如果出现红色的Disabled，就需要在php.ini配置文件里把对应的配置改为On。
点击"Create/Reset Database"按钮开始安装DVWA。

默认账号密码=>admin/password

burp启动器=>https://pan.baidu.com/s/1z74XktGeNNwMETp0wi8Sow?pwd=6666
JDK18=>https://pan.baidu.com/s/1udm55kcdP0zd9ucO7SeTVg?pwd=6666

sqlmap=>https://github.com/sqlmapproject/sqlmap
