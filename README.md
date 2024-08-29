# Awesome AI for DB papers

<!-- vim-markdown-toc GFM -->

* [Database configuration](#database-configuration)
    * [Configuration tunning](#configuration-tunning)
    * [Index advisor](#index-advisor)
* [Query optimization](#query-optimization)
    * [Steering query optimizer](#steering-query-optimizer)
    * [Execution time prediction](#execution-time-prediction)
* [Performance diagnosis](#performance-diagnosis)

<!-- vim-markdown-toc -->

## Database configuration

### Configuration tunning

- [Db2une: Tuning Under Pressure via Deep Learning](https://www.vldb.org/pvldb/vol17/p3855-bianchi.pdf), VLDB 2024

### Index advisor

- [Breaking It Down: An In-depth Study of Index Advisors](https://www.vldb.org/pvldb/vol17/p2405-li.pdf), VLDB 2024

## Query optimization

### Steering query optimizer

Learn an optimizer hint/rule configuration to reduce query optimization and execution latency, and save execution resources.

- [AutoSteer: Learned Query Optimization for Any SQL Database](https://www.vldb.org/pvldb/vol16/p3515-anneser.pdf), VLDB 2023
- [Steering Query Optimizers: A Practical Take on Big Data Workloads](https://dl.acm.org/doi/pdf/10.1145/3448016.3457568), SIGMOD 2021
- [Bao: Making Learned Query Optimization Practical](https://15799.courses.cs.cmu.edu/spring2022/papers/17-queryopt1/marcus-sigmod2021.pdf), SIGMOD 2021

### Execution time prediction

Predicting the execution time of a query before actually executing the query is a crucial component for many tasks in intelligent cloud DBMSs, such as query optimization, workload scheduling, admission control, resource management, and maintaining SLAs.

- [Stage: Query Execution Time Prediction in Amazon Redshift](https://dl.acm.org/doi/pdf/10.1145/3626246.3653391), SIGMOD 2024

## Performance diagnosis

- [D-Bot: Database Diagnosis System using Large Language Models](https://dbgroup.cs.tsinghua.edu.cn/ligl//papers/dbot_vldb_camera_ready_v1.pdf), VLDB 2024
- [Diagnosing Root Causes of Intermittent Slow Queries in Cloud Databases](https://www.vldb.org/pvldb/vol13/p1176-ma.pdf), VLDB 2020
