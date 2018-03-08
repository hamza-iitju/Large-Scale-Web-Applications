# Large-Scale-Web-Applications
## Performance
### Average Page Load Time
Average Page Load Time as a fraction of Server and client time, Network time, Page views, Bounce Rate, Percentage Exit, Average Redirection Time, Average Domain Lookup Time, Average Server Connection Time, Average Server Response Time, Average Page Download Time, Average content load time, Average session time, DNS resolution time, TCP connection time, Time to first byte, Full page object load time, Requests per second, error rates, Peak response time, Uptime, CPU utilization, Memory Utilization are just a few metrics to look for.

## Availability -- Business continuity
### Availability Techniques
AlwaysOn Failover Cluster Instances, AlwaysOn Availability Groups, Database mirroring, Log shipping, Redundancy models - Active-Active, Active-Passive, Redundancy Methods - Hot Standby, Warm Standby, Cold Standby, and the measurement of the same expressed as mean time to failure, mean time to repair, Eliminating single points of failure, Accelerating fault detection, isolation and resolution, hot spares, warm spares, cold spares, clustering, RAID, redundancy, Heart beats, watermarking resources, check pointing, Watch dogs and more.

## Monitoring and Diagnostics
26 front end proxy serves. Double that in backend app servers [Atlassian HipChat], 15,000+ hardware systems – [Salesforce], 100 hardware nodes in production – [CinchCast], 180 Web Engines + 240 API Engines, 88 MySQL DBs (cc2.8xlarge) + 1 slave each, 110 Redis Instances, 200 Memcache Instances, 4 Redis Task Manager + 80 Task Processors, Sharded Solr – [Pinterest], 1000+ supported devices – [Netflix].

## Scalability
Capability of supporting and optimizing resource utilization on increasing workloads on various dimensions such as memory, cores, data structures, throughout and more.

## Automation
Logical segregation of layers in current large scale web applications.   
![myimage-alt-tag](https://github.com/hamza-iitju/Large-Scale-Web-Applications/blob/master/logical%20segregation%20of%20layers.png)

## For Scalable Websites
Parallel processing - Explicit and Implicit parallelism, batch  parallelism, asynchronous programming, segregating layers, distributing workloads, Load balancing, multi- tenancy, scaling out on all layers, sharding, partitioning, CAP preference, reads, writes, statelessness, logging and telemetry, automating, SOA adoption, caching, throttling, distributing requests across multiple zones, effective usage of CDNs, Auto provisioning, Auto scaling, compression, queuing, workload distribution, batch processing, designing system with fault tolerance, redundancy, Consistency, Availability, Partition Tolerance, event processing, web sockets, cloud computing, fog computing, Grid Computing,  Client side workload distribution, In-Memory processing, Proxies, No single points of failure. Resilience to failure, Graceful degradation, Recoverability from failure, design for failure, Database Transactions, Client side transactions, two-phase commit, Auto-commit, Partition Everything, DB operations ordering, Considerations for Eventual consistency, Functional Segmentation, Application Pools, Prevention of session state, Async Everywhere, Index, Structured Indexes, text indexes, entity indexes, Fuzzy match indexes, pre-aggregated indexes, pre-calculated indexes, embedded value indexes, join indexes, link indexes, De-Normalized Indexes (all kinds) are all important considerations for a highly successful and scalable website.


Ref: https://www.linkedin.com/pulse/architecting-extremely-large-scale-web-applications-panduranga?trk=mp-reader-card
