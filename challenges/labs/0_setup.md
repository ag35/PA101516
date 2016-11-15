Region: US East, N. Virginia
OS: Centos 6.5

[root@ip-172-31-53-128 ~]# ls -lrt /usr/java
ls: cannot access /usr/java: No such file or directory

MySQL Node (N1):
172.31.53.128   ip-172-31-53-128.ec2.internal 

[root@ip-172-31-53-128 ~]# for I in 1 2 3 4 5 6 7 ; do echo N${I}; ssh N${I} "cat /etc/passwd | egrep 'kang|kidis'" ; done   N1
kang:x:2500:2500::/home/kang:/bin/bash
N2
kang:x:2500:2500::/home/kang:/bin/bash
N3
kang:x:2500:2500::/home/kang:/bin/bash
N4
kang:x:2500:2500::/home/kang:/bin/bash
N5
kang:x:2500:2500::/home/kang:/bin/bash

[root@ip-172-31-53-128 ~]# for I in 1 2 3 4 5 6 7 ; do echo N${I}; ssh N${I} "cat /etc/group | egrep 'destroy|enslave'" ; done
N1
destroy:x:2502:kodos
enslave:x:2503:kang
N2
destroy:x:2502:kodos
enslave:x:2503:kang
N3
destroy:x:2502:kodos
enslave:x:2503:kang
N4
destroy:x:2502:kodos
enslave:x:2503:kang
N5
destroy:x:2502:kodos
enslave:x:2503:kang
