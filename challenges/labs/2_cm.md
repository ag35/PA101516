```
[root@ip-172-31-53-129 yum.repos.d]# ls -lrt /etc/yum.repos.d/
total 32
-rw-r--r--. 1 root root 3664 Nov 27  2013 CentOS-Vault.repo
-rw-r--r--. 1 root root  630 Nov 27  2013 CentOS-Media.repo
-rw-r--r--. 1 root root  638 Nov 27  2013 CentOS-Debuginfo.repo
-rw-r--r--. 1 root root 1926 Nov 27  2013 CentOS-Base.repo
-rw-r--r--  1 root root 1440 Sep 12 06:32 mysql-community-source.repo
-rw-r--r--  1 root root  294 Nov 14 21:26 cloudera-manager.repo
-rw-r--r--  1 root root 1414 Nov 14 21:43 mysql-community.repo
-rw-r--r--  1 root root 3575 Nov 14 22:06 log4j.log

create user 'scm'@'ip-172-31-53-129.ec2.internal' identified by 'scm';
Query OK, 0 rows affected (0.00 sec)

mysql> grant all on scm.* to ip-172-31-53-129.ec2.internal' ;

[root@ip-172-31-53-129 ~]# head -1 /var/log/cloudera-scm-server/cloudera-scm-server.log
2016-11-14 22:07:10,084 INFO main:com.cloudera.server.cmf.Main: Starting SCM Server. JVM Args: [-Dlog4j.configuration=file:/etc/cloudera-scm-server/log4j.properties, -Dfile.encoding=UTF-8, -Dcmf.root.logger=INFO,LOGFILE, -Dcmf.log.dir=/var/log/cloudera-scm-server, -Dcmf.log.file=cloudera-scm-server.log, -Dcmf.jetty.threshhold=WARN, -Dcmf.schema.dir=/usr/share/cmf/schema, -Djava.awt.headless=true, -Djava.net.preferIPv4Stack=true, -Dpython.home=/usr/share/cmf/python, -XX:+UseConcMarkSweepGC, -XX:+UseParNewGC, -XX:+HeapDumpOnOutOfMemoryError, -Xmx2G, -XX:MaxPermSize=256m, -XX:+HeapDumpOnOutOfMemoryError, -XX:HeapDumpPath=/tmp, -XX:OnOutOfMemoryError=kill -9 %p], Args: [], Version: 5.8.1 (#7 built by jenkins on 20160722-1141 git: a0886a893750079a4dc7f902be22d6f6e63b85a1)

[root@ip-172-31-53-129 ~]# grep "Started Jetty server" /var/log/cloudera-scm-server/cloudera-scm-server.log
2016-11-14 22:09:23,339 INFO WebServerImpl:com.cloudera.server.cmf.WebServerImpl: Started Jetty server.



```