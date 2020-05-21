centos 7 添加阿里云镜像
wget -O /etc/yum.repos.d/CentOS-Base.repo http://mirrors.aliyun.com/repo/Centos-7.repo
yum install epel-release

安装常用的开发组件
yum  groups install "Development Tools"
yum groups info  "Development Tools"

关闭SElinux
systemctl stop firewalld.service
systemctl disable  firewalld.service
vim /etc/selinux/config
