（1）首先安装需要安装git

yum install git -y
1
（2）将GitHub项目下载到服务器

git clone https://github.com/IWanalq/openvpn-install
1
（3）进入openvpn目录

cd openvpn
1
（4）安装openvpn

bash openvpn-install.sh
1
（5）自定义端口(选择Custom 然后输入67)，协议(UDP协议)，其余一路回车

（6）添加用户、移除用户

bash openvpn-install.sh
或./openvpn-istall.sh
1
2


（7）用户添加成功，会在/root目录下生成用户名.ovpn使用“sz”命令下载到本地

（8）将配置文件导入Open安装目录中的config下
————————————————
版权声明：本文为CSDN博主「遇见流光」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/m0_53129012/article/details/111173610
