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

[root@fs2client01 ~]# yum repolist
Loaded plugins: fastestmirror, langpacks
local.repo                                               | 3.6 kB     00:00
(1/2): local.repo/group_gz                                 | 155 kB   00:00
(2/2): local.repo/primary_db                               | 5.3 MB   00:00
Determining fastest mirrors
repo id                              repo name                            status
local.repo                           local.repo                           9,007
repolist: 9,007
[root@fs2client01 ~]#


