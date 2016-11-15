```
 time hadoop jar /usr/lib/hadoop-0.20-mapreduce/hadoop-examples.jar teragen -D dfs.block.size=33554432 51200000 /user/kang/tgen64

real    2m30.533s
user    0m6.248s
sys     0m0.690s

[kang@ip-172-31-53-128 ~]$ hdfs dfs -ls /user/kang/tgen64
Found 3 items
-rw-r--r--   3 kang supergroup          0 2016-11-14 22:51 /user/kang/tgen64/_SUCCESS
-rw-r--r--   3 kang supergroup 2560000000 2016-11-14 22:51 /user/kang/tgen64/part-m-00000
-rw-r--r--   3 kang supergroup 2560000000 2016-11-14 22:51 /user/kang/tgen64/part-m-00001


51200000 * 100 bytes = 5120000000 bytes / 33554432 bytes (32mb) = 153 blocks (aproximately) 

```