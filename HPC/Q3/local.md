for c07n1
[root@fs2client01 yum.repos.d]# cat local.repo
[local.repo]
name=local.repo
baseurl=http://10.10.10.254/centos/x86_64/7.2_extras/
enabled=1
gpgcheck=0
[root@fs2client01 yum.repos.d]#

login as: root
root@10.10.10.66's password:
Last login: Fri Feb 10 01:40:51 2017 from c18n2.netwebdel.com
[root@fs2client01 ~]# cat /etc/yum.repos.d/local.repo
[local.repo]
name=local.repo
baseurl=http://10.10.10.254/centos/x86_64/7.2/
enabled=1
gpgcheck=0


[root@fs2client01 ~]#

