```
[kodos@ip-172-31-53-128 ~]$ hadoop jar /usr/lib/hadoop-0.20-mapreduce/hadoop-examples.jar pi 1 1000
Number of Maps  = 1
Samples per Map = 1000
Wrote input for Map #0
Starting Job
16/11/14 23:16:29 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-53-128.ec2.internal/172.31.53.128:8032
16/11/14 23:16:30 INFO hdfs.DFSClient: Created HDFS_DELEGATION_TOKEN token 2 for kodos on 172.31.53.128:8020
16/11/14 23:16:30 INFO security.TokenCache: Got dt for hdfs://ip-172-31-53-128.ec2.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.53.128:8020, Ident: (HDFS_DELEGATION_TOKEN token 2 for kodos)
16/11/14 23:16:30 INFO input.FileInputFormat: Total input paths to process : 1
16/11/14 23:16:30 INFO mapreduce.JobSubmitter: number of splits:1
16/11/14 23:16:30 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1479182994400_0002
16/11/14 23:16:30 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.53.128:8020, Ident: (HDFS_DELEGATION_TOKEN token 2 for kodos)
16/11/14 23:16:31 INFO impl.YarnClientImpl: Submitted application application_1479182994400_0002
16/11/14 23:16:31 INFO mapreduce.Job: The url to track the job: http://ip-172-31-53-128.ec2.internal:8088/proxy/application_1479182994400_0002/
16/11/14 23:16:31 INFO mapreduce.Job: Running job: job_1479182994400_0002
16/11/14 23:16:49 INFO mapreduce.Job: Job job_1479182994400_0002 running in uber mode : false
16/11/14 23:16:49 INFO mapreduce.Job:  map 0% reduce 0%
16/11/14 23:16:58 INFO mapreduce.Job:  map 100% reduce 0%
16/11/14 23:17:11 INFO mapreduce.Job:  map 100% reduce 100%
16/11/14 23:17:12 INFO mapreduce.Job: Job job_1479182994400_0002 completed successfully
16/11/14 23:17:13 INFO mapreduce.Job: Counters: 49
        File System Counters
                FILE: Number of bytes read=38
                FILE: Number of bytes written=243287
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=285
                HDFS: Number of bytes written=215
                HDFS: Number of read operations=7
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=3
        Job Counters
                Launched map tasks=1
                Launched reduce tasks=1
                Data-local map tasks=1
                Total time spent by all maps in occupied slots (ms)=6730
                Total time spent by all reduces in occupied slots (ms)=9397
                Total time spent by all map tasks (ms)=6730
                Total time spent by all reduce tasks (ms)=9397
                Total vcore-seconds taken by all map tasks=6730
                Total vcore-seconds taken by all reduce tasks=9397
                Total megabyte-seconds taken by all map tasks=6891520
                Total megabyte-seconds taken by all reduce tasks=9622528
        Map-Reduce Framework
                Map input records=1
                Map output records=2
                Map output bytes=18
                Map output materialized bytes=34
                Input split bytes=167
                Combine input records=0
                Combine output records=0
                Reduce input groups=2
                Reduce shuffle bytes=34
                Reduce input records=2
                Reduce output records=0
                Spilled Records=4
                Shuffled Maps =1
                Failed Shuffles=0
                Merged Map outputs=1
                GC time elapsed (ms)=85
                CPU time spent (ms)=1980
                Physical memory (bytes) snapshot=653529088
                Virtual memory (bytes) snapshot=3131195392
                Total committed heap usage (bytes)=803209216
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=118
        File Output Format Counters
                Bytes Written=97
Job Finished in 43.359 seconds
Estimated value of Pi is 3.14800000000000000000
```