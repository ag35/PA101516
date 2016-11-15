```
0: jdbc:hive2://ip-172-31-53-128.ec2.internal> show tables;
INFO  : Compiling command(queryId=hive_20161114233737_29643f6a-8250-4c8b-b23d-b541aca377e3): show tables
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : Completed compiling command(queryId=hive_20161114233737_29643f6a-8250-4c8b-b23d-b541aca377e3); Time taken: 0.324 seconds
INFO  : Executing command(queryId=hive_20161114233737_29643f6a-8250-4c8b-b23d-b541aca377e3): show tables
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20161114233737_29643f6a-8250-4c8b-b23d-b541aca377e3); Time taken: 0.265 seconds
INFO  : OK
+------------+--+
|  tab_name  |
+------------+--+
| customers  |
| sample_07  |
| sample_08  |
| web_logs   |
+------------+--+
4 rows selected (0.789 seconds)

0: jdbc:hive2://ip-172-31-53-128.ec2.internal> show tables;
INFO  : Compiling command(queryId=hive_20161114233939_9e78629e-209c-4d3d-aa90-b6187fb52b46): show tables
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : Completed compiling command(queryId=hive_20161114233939_9e78629e-209c-4d3d-aa90-b6187fb52b46); Time taken: 0.062 seconds
INFO  : Executing command(queryId=hive_20161114233939_9e78629e-209c-4d3d-aa90-b6187fb52b46): show tables
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20161114233939_9e78629e-209c-4d3d-aa90-b6187fb52b46); Time taken: 0.149 seconds
INFO  : OK
+------------+--+
|  tab_name  |
+------------+--+
| customers  |
| sample_07  |
| sample_08  |
| web_logs   |
+------------+--+
4 rows selected (0.331 seconds)



```