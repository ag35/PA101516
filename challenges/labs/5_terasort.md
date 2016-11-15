```
[kang@ip-172-31-53-128 ~]$ hadoop jar /usr/lib/hadoop-0.20-mapreduce/hadoop-examples.jar terasort /user/kang/tgen64 /user/kang/tsort64
16/11/14 23:14:58 INFO terasort.TeraSort: starting
16/11/14 23:15:00 INFO hdfs.DFSClient: Created HDFS_DELEGATION_TOKEN token 1 for kang on 172.31.53.128:8020
16/11/14 23:15:00 INFO security.TokenCache: Got dt for hdfs://ip-172-31-53-128.ec2.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.53.128:8020, Ident: (HDFS_DELEGATION_TOKEN token 1 for kang)
16/11/14 23:15:00 INFO input.FileInputFormat: Total input paths to process : 2
Spent 368ms computing base-splits.
Spent 4ms computing TeraScheduler splits.
Computing input splits took 373ms
Sampling 10 splits of 154
Making 10 from 100000 sampled records
Computing parititions took 1302ms
Spent 1677ms computing partitions.
16/11/14 23:15:01 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-53-128.ec2.internal/172.31.53.128:8032
16/11/14 23:15:02 INFO mapreduce.JobSubmitter: number of splits:154
16/11/14 23:15:02 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1479182994400_0001
16/11/14 23:15:02 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.53.128:8020, Ident: (HDFS_DELEGATION_TOKEN token 1 for kang)
16/11/14 23:15:03 INFO impl.YarnClientImpl: Submitted application application_1479182994400_0001
16/11/14 23:15:03 INFO mapreduce.Job: The url to track the job: http://ip-172-31-53-128.ec2.internal:8088/proxy/application_1479182994400_0001/
16/11/14 23:15:03 INFO mapreduce.Job: Running job: job_1479182994400_0001
16/11/14 23:15:14 INFO mapreduce.Job: Job job_1479182994400_0001 running in uber mode : false
16/11/14 23:15:14 INFO mapreduce.Job:  map 0% reduce 0%
16/11/14 23:15:24 INFO mapreduce.Job:  map 1% reduce 0%
16/11/14 23:15:26 INFO mapreduce.Job:  map 2% reduce 0%
16/11/14 23:15:27 INFO mapreduce.Job:  map 3% reduce 0%
16/11/14 23:15:30 INFO mapreduce.Job:  map 4% reduce 0%
16/11/14 23:15:33 INFO mapreduce.Job:  map 8% reduce 0%
16/11/14 23:15:38 INFO mapreduce.Job:  map 10% reduce 0%
16/11/14 23:15:40 INFO mapreduce.Job:  map 11% reduce 0%
16/11/14 23:15:41 INFO mapreduce.Job:  map 12% reduce 0%
16/11/14 23:15:44 INFO mapreduce.Job:  map 14% reduce 0%
16/11/14 23:15:45 INFO mapreduce.Job:  map 15% reduce 0%
16/11/14 23:15:47 INFO mapreduce.Job:  map 17% reduce 0%
16/11/14 23:15:49 INFO mapreduce.Job:  map 18% reduce 0%
16/11/14 23:15:51 INFO mapreduce.Job:  map 19% reduce 0%
16/11/14 23:15:54 INFO mapreduce.Job:  map 20% reduce 0%
16/11/14 23:15:55 INFO mapreduce.Job:  map 21% reduce 0%
16/11/14 23:15:56 INFO mapreduce.Job:  map 23% reduce 0%
16/11/14 23:15:58 INFO mapreduce.Job:  map 25% reduce 0%
16/11/14 23:16:04 INFO mapreduce.Job:  map 27% reduce 0%
16/11/14 23:16:05 INFO mapreduce.Job:  map 29% reduce 0%
16/11/14 23:16:06 INFO mapreduce.Job:  map 30% reduce 0%
16/11/14 23:16:07 INFO mapreduce.Job:  map 31% reduce 0%
16/11/14 23:16:11 INFO mapreduce.Job:  map 32% reduce 0%
16/11/14 23:16:13 INFO mapreduce.Job:  map 33% reduce 0%
16/11/14 23:16:14 INFO mapreduce.Job:  map 34% reduce 0%
16/11/14 23:16:15 INFO mapreduce.Job:  map 36% reduce 0%
16/11/14 23:16:16 INFO mapreduce.Job:  map 37% reduce 0%
16/11/14 23:16:17 INFO mapreduce.Job:  map 38% reduce 0%
16/11/14 23:16:21 INFO mapreduce.Job:  map 39% reduce 0%
16/11/14 23:16:22 INFO mapreduce.Job:  map 40% reduce 0%
16/11/14 23:16:23 INFO mapreduce.Job:  map 42% reduce 0%
16/11/14 23:16:25 INFO mapreduce.Job:  map 43% reduce 0%
16/11/14 23:16:26 INFO mapreduce.Job:  map 44% reduce 0%
16/11/14 23:16:29 INFO mapreduce.Job:  map 45% reduce 0%
16/11/14 23:16:31 INFO mapreduce.Job:  map 47% reduce 0%
16/11/14 23:16:35 INFO mapreduce.Job:  map 49% reduce 0%
16/11/14 23:16:36 INFO mapreduce.Job:  map 50% reduce 0%
16/11/14 23:16:37 INFO mapreduce.Job:  map 52% reduce 0%
16/11/14 23:16:39 INFO mapreduce.Job:  map 53% reduce 0%
16/11/14 23:16:42 INFO mapreduce.Job:  map 54% reduce 0%
16/11/14 23:16:44 INFO mapreduce.Job:  map 55% reduce 0%
16/11/14 23:16:45 INFO mapreduce.Job:  map 56% reduce 0%
16/11/14 23:16:47 INFO mapreduce.Job:  map 58% reduce 0%
16/11/14 23:16:49 INFO mapreduce.Job:  map 59% reduce 0%
16/11/14 23:16:50 INFO mapreduce.Job:  map 60% reduce 0%
16/11/14 23:16:53 INFO mapreduce.Job:  map 61% reduce 0%
16/11/14 23:16:55 INFO mapreduce.Job:  map 63% reduce 0%
16/11/14 23:16:56 INFO mapreduce.Job:  map 64% reduce 0%
16/11/14 23:17:00 INFO mapreduce.Job:  map 65% reduce 0%
16/11/14 23:17:01 INFO mapreduce.Job:  map 66% reduce 0%
16/11/14 23:17:03 INFO mapreduce.Job:  map 68% reduce 0%
16/11/14 23:17:05 INFO mapreduce.Job:  map 69% reduce 0%
16/11/14 23:17:09 INFO mapreduce.Job:  map 70% reduce 0%
16/11/14 23:17:10 INFO mapreduce.Job:  map 71% reduce 0%
16/11/14 23:17:11 INFO mapreduce.Job:  map 73% reduce 0%
16/11/14 23:17:13 INFO mapreduce.Job:  map 74% reduce 0%
16/11/14 23:17:16 INFO mapreduce.Job:  map 75% reduce 0%
16/11/14 23:17:18 INFO mapreduce.Job:  map 76% reduce 0%
16/11/14 23:17:19 INFO mapreduce.Job:  map 77% reduce 0%
16/11/14 23:17:20 INFO mapreduce.Job:  map 79% reduce 0%
16/11/14 23:17:23 INFO mapreduce.Job:  map 80% reduce 0%
16/11/14 23:17:24 INFO mapreduce.Job:  map 81% reduce 0%
16/11/14 23:17:27 INFO mapreduce.Job:  map 82% reduce 0%
16/11/14 23:17:28 INFO mapreduce.Job:  map 84% reduce 0%
16/11/14 23:17:30 INFO mapreduce.Job:  map 86% reduce 0%
16/11/14 23:17:37 INFO mapreduce.Job:  map 87% reduce 0%
16/11/14 23:17:38 INFO mapreduce.Job:  map 88% reduce 6%
16/11/14 23:17:40 INFO mapreduce.Job:  map 88% reduce 15%
16/11/14 23:17:43 INFO mapreduce.Job:  map 89% reduce 15%
16/11/14 23:17:44 INFO mapreduce.Job:  map 90% reduce 15%
16/11/14 23:17:50 INFO mapreduce.Job:  map 91% reduce 15%
16/11/14 23:17:51 INFO mapreduce.Job:  map 93% reduce 15%
16/11/14 23:17:58 INFO mapreduce.Job:  map 94% reduce 15%
16/11/14 23:17:59 INFO mapreduce.Job:  map 95% reduce 16%
16/11/14 23:18:05 INFO mapreduce.Job:  map 96% reduce 16%
16/11/14 23:18:06 INFO mapreduce.Job:  map 97% reduce 16%
16/11/14 23:18:09 INFO mapreduce.Job:  map 98% reduce 16%
16/11/14 23:18:11 INFO mapreduce.Job:  map 99% reduce 16%
16/11/14 23:18:14 INFO mapreduce.Job:  map 100% reduce 16%
16/11/14 23:18:15 INFO mapreduce.Job:  map 100% reduce 17%
16/11/14 23:18:16 INFO mapreduce.Job:  map 100% reduce 20%
16/11/14 23:18:17 INFO mapreduce.Job:  map 100% reduce 28%
16/11/14 23:18:18 INFO mapreduce.Job:  map 100% reduce 30%
16/11/14 23:18:19 INFO mapreduce.Job:  map 100% reduce 32%
16/11/14 23:18:20 INFO mapreduce.Job:  map 100% reduce 35%
16/11/14 23:18:21 INFO mapreduce.Job:  map 100% reduce 42%
16/11/14 23:18:23 INFO mapreduce.Job:  map 100% reduce 53%
16/11/14 23:18:24 INFO mapreduce.Job:  map 100% reduce 56%
16/11/14 23:18:26 INFO mapreduce.Job:  map 100% reduce 60%
16/11/14 23:18:27 INFO mapreduce.Job:  map 100% reduce 63%
16/11/14 23:18:28 INFO mapreduce.Job:  map 100% reduce 65%
16/11/14 23:18:29 INFO mapreduce.Job:  map 100% reduce 72%
16/11/14 23:18:30 INFO mapreduce.Job:  map 100% reduce 73%
16/11/14 23:18:31 INFO mapreduce.Job:  map 100% reduce 74%
16/11/14 23:18:32 INFO mapreduce.Job:  map 100% reduce 80%
16/11/14 23:18:33 INFO mapreduce.Job:  map 100% reduce 81%
16/11/14 23:18:35 INFO mapreduce.Job:  map 100% reduce 83%
16/11/14 23:18:36 INFO mapreduce.Job:  map 100% reduce 85%
16/11/14 23:18:37 INFO mapreduce.Job:  map 100% reduce 91%
16/11/14 23:18:38 INFO mapreduce.Job:  map 100% reduce 92%
16/11/14 23:18:39 INFO mapreduce.Job:  map 100% reduce 93%
16/11/14 23:18:40 INFO mapreduce.Job:  map 100% reduce 94%
16/11/14 23:18:41 INFO mapreduce.Job:  map 100% reduce 95%
16/11/14 23:18:43 INFO mapreduce.Job:  map 100% reduce 96%
16/11/14 23:18:49 INFO mapreduce.Job:  map 100% reduce 97%
16/11/14 23:18:50 INFO mapreduce.Job:  map 100% reduce 98%
16/11/14 23:18:55 INFO mapreduce.Job:  map 100% reduce 99%
16/11/14 23:19:03 INFO mapreduce.Job:  map 100% reduce 100%
16/11/14 23:19:07 INFO mapreduce.Job: Job job_1479182994400_0001 completed successfully
16/11/14 23:19:07 INFO mapreduce.Job: Counters: 49
        File System Counters
                FILE: Number of bytes read=2287019884
                FILE: Number of bytes written=4547150875
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=5120020944
                HDFS: Number of bytes written=5120000000
                HDFS: Number of read operations=492
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=20
        Job Counters
                Launched map tasks=154
                Launched reduce tasks=10
                Data-local map tasks=154
                Total time spent by all maps in occupied slots (ms)=1134126
                Total time spent by all reduces in occupied slots (ms)=436686
                Total time spent by all map tasks (ms)=1134126
                Total time spent by all reduce tasks (ms)=436686
                Total vcore-seconds taken by all map tasks=1134126
                Total vcore-seconds taken by all reduce tasks=436686
                Total megabyte-seconds taken by all map tasks=1161345024
                Total megabyte-seconds taken by all reduce tasks=447166464
        Map-Reduce Framework
                Map input records=51200000
                Map output records=51200000
                Map output bytes=5222400000
                Map output materialized bytes=2240045957
                Input split bytes=20944
                Combine input records=0
                Combine output records=0
                Reduce input groups=51200000
                Reduce shuffle bytes=2240045957
                Reduce input records=51200000
                Reduce output records=51200000
                Spilled Records=102400000
                Shuffled Maps =1540
                Failed Shuffles=0
                Merged Map outputs=1540
                GC time elapsed (ms)=16347
                CPU time spent (ms)=744670
                Physical memory (bytes) snapshot=81353728000
                Virtual memory (bytes) snapshot=257447407616
                Total committed heap usage (bytes)=93873242112
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=5120000000
        File Output Format Counters
                Bytes Written=5120000000
16/11/14 23:19:07 INFO terasort.TeraSort: done
```