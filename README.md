# one-key-kms
在Linux上一键搭建KMS服务器

特别感谢KMS服务器程序的开发者Wind4


KMS服务器软件vlmcsd Github主页：https://github.com/Wind4/vlmcsd

`现在还处于测试阶段，您的服务器出现任何问题本人与服务器程序作者均不承担任何责任。`

请根据自己的服务器操作系统运行对应的脚本。

CentOS，Redhat，Fedora等请选择CentOS脚本

Debian，Ubuntu，Mint等请选择Debian脚本

##kms.sh管理脚本的使用：

如果您使用这里的一键脚本安装，即可完美使用该脚本，否则需要手动更改可执行文件存放路径

只有start/stop/restart/status的功能，直接执行即可

./kms.sh start

这样。


<h2 id="搭建教程">搭建教程</h2>

<p>CentOS，Redhat，Fedora等请选择CentOS脚本</p>

<code>wget https://raw.githubusercontent.com/dakkidaze/one-key-kms/master/one-key-kms-centos.sh
chmod +x one-key-kms-centos.sh
./one-key-kms-centos.sh</code>

wget https://raw.githubusercontent.com/dakkidaze/one-key-kms/master/one-key-kms-centos.sh
chmod +x one-key-kms-centos.sh
./one-key-kms-centos.sh
Debian，Ubuntu，Mint等请选择Debian脚本

wget https://raw.githubusercontent.com/dakkidaze/one-key-kms/master/one-key-kms-debian.sh
chmod +x one-key-kms-debian.sh
./one-key-kms-debian.sh
1
2
3
wget https://raw.githubusercontent.com/dakkidaze/one-key-kms/master/one-key-kms-debian.sh
chmod +x one-key-kms-debian.sh
./one-key-kms-debian.sh
启动KMS

wget https://raw.githubusercontent.com/dakkidaze/one-key-kms/master/kms.sh
chmod +x kms.sh
./kms.sh start
1
2
3
wget https://raw.githubusercontent.com/dakkidaze/one-key-kms/master/kms.sh
chmod +x kms.sh
./kms.sh start
这里的kms.sh还可以使用 start/stop/restart/status的功能来管理KMS服务器。

安装完成后，输入以下命令查看端口号 1688 的监听情况

netstat -nxtlp | grep 1688
1
netstat -nxtlp | grep 1688
