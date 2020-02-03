# How To Install kloxo-mr

Based on Kloxo by Mustafa Ramadhan

yum -y update <br />
yum -y upgrade<br />

setenforce 0<br />
echo ‘SELINUX=disabled’ > /etc/selinux/config<br />

yum install yum-utils yum-priorities vim-minimal subversion curl zip unzip -y<br />
yum install telnet wget -y<br />

cd /etc/yum.repos.d/<br />
rpm -ivh https://github.com/mustafaramadhan/rpms/raw/master/mratwork/release/neutral/noarch/mratwork-release-0.0.1-1.noarch.rpm<br />

yum update mratwork-*<br />

yum install kloxomr7 -y<br />
sh /script/upcp<br />
sh /script/restart-all<br />

Login to Your Kloxo

http://localhost:7778<br />
https://localhost:777<br />

<a href="https://content.id">content</a> about
<a href="https://resort.id">resort</a> at
<a href="https://zero.id">zero.id</a>


