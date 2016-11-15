```
mysql> show grants for rman;
+-----------------------------------------------------------------------------------------------------+
| Grants for rman@%                                                                                   |
+-----------------------------------------------------------------------------------------------------+
| GRANT USAGE ON *.* TO 'rman'@'%' IDENTIFIED BY PASSWORD '*819397F8B454D58DA4E9F42A88A4873756B8C96D' |
| GRANT ALL PRIVILEGES ON `rman`.* TO 'rman'@'%'                                                      |
+-----------------------------------------------------------------------------------------------------+
2 rows in set (0.00 sec)

mysql> show grants for hive;
+-----------------------------------------------------------------------------------------------------+
| Grants for hive@%                                                                                   |
+-----------------------------------------------------------------------------------------------------+
| GRANT USAGE ON *.* TO 'hive'@'%' IDENTIFIED BY PASSWORD '*4DF1D66463C18D44E3B001A8FB1BBFBEA13E27FC' |
| GRANT ALL PRIVILEGES ON `hive`.* TO 'hive'@'%'                                                      |
+-----------------------------------------------------------------------------------------------------+
2 rows in set (0.00 sec)

mysql> show grants for oozie;
+------------------------------------------------------------------------------------------------------+
| Grants for oozie@%                                                                                   |
+------------------------------------------------------------------------------------------------------+
| GRANT USAGE ON *.* TO 'oozie'@'%' IDENTIFIED BY PASSWORD '*2B03FE0359FAD3B80620490CE614F8622E0828CD' |
| GRANT ALL PRIVILEGES ON `oozie`.* TO 'oozie'@'%'                                                     |
+------------------------------------------------------------------------------------------------------+
2 rows in set (0.00 sec)

-bash-4.1$ hdfs dfs -ls /user
Found 4 items
drwxrwxrwx   - mapred hadoop              0 2016-11-14 22:39 /user/history
drwxrwxr-t   - hive   hive                0 2016-11-14 22:40 /user/hive
drwxr-xr-x   - kang   supergroup          0 2016-11-14 22:39 /user/kang
drwxr-xr-x   - kodos  supergroup          0 2016-11-14 22:39 /user/kodos

{
  "items" : [ {
    "hostId" : "i-09a86b75f937e7f51",
    "ipAddress" : "172.31.53.128",
    "hostname" : "ip-172-31-53-128.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-53-129.ec2.internal:7180/cmf/hostRedirect/i-09a86b75f937e7f51",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 4,
    "totalPhysMemBytes" : 15740305408
  }, {
    "hostId" : "i-09dfd88ba315ffb17",
    "ipAddress" : "172.31.53.129",
    "hostname" : "ip-172-31-53-129.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-53-129.ec2.internal:7180/cmf/hostRedirect/i-09dfd88ba315ffb17",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 4,
    "totalPhysMemBytes" : 15740305408
  }, {
    "hostId" : "i-09e3f01cb58304566",
    "ipAddress" : "172.31.53.130",
    "hostname" : "ip-172-31-53-130.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-53-129.ec2.internal:7180/cmf/hostRedirect/i-09e3f01cb58304566",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 4,
    "totalPhysMemBytes" : 15740305408
  }, {
    "hostId" : "i-095bc43556e955e9a",
    "ipAddress" : "172.31.53.131",
    "hostname" : "ip-172-31-53-131.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-53-129.ec2.internal:7180/cmf/hostRedirect/i-095bc43556e955e9a",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 4,
    "totalPhysMemBytes" : 15740305408
  }, {
    "hostId" : "i-02b9325b31234dd63",
    "ipAddress" : "172.31.53.132",
    "hostname" : "ip-172-31-53-132.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-53-129.ec2.internal:7180/cmf/hostRedirect/i-02b9325b31234dd63",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 4,
    "totalPhysMemBytes" : 15740305408
  } ]
}


```