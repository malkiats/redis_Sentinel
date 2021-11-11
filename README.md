1. Redis is an in-memory database structure use it as a database cache and message broker for high performance and replication, persistance on disk, client side sharding, transaction and queuing.
2. no sequel or simply non rational, register is no table and there is no database

# Use cases
1. Store Sessions, Item stored in shopping cart
2. Html, Json HTML fragments
3. Queues or task scheduling
4. Metro billing 
5. Social Networking Sites
6. Gaming App scoreboards
7. Geo Hashing

# Redis sentinel
1. Robust distributed system.
2. Multiple sentinels need to agree about the fact a given master is no longer available. And then failover process starts to select a new MASTER node.
3. This Sentinel agreement is done according to the quorum value.
4. Quron is number if santino that needs to agree about the fact that the master is not reachable in order to really mark the master as failing and start avialable process.
![image](https://user-images.githubusercontent.com/43002915/141262080-dbd44485-a33e-4bec-8f74-d2bfec536ca7.png)


![image](https://user-images.githubusercontent.com/43002915/141262463-6c35883b-70e0-47f8-92f5-357fedfa34a3.png)


![image](https://user-images.githubusercontent.com/43002915/141264588-71ca92d0-e5a8-4359-a762-61856535b7ae.png)


![image](https://user-images.githubusercontent.com/43002915/141267673-13cd09d0-2853-489d-8ab2-03f50f50487b.png)


![image](https://user-images.githubusercontent.com/43002915/141301136-427b8d53-fef1-4c6b-8422-e03088eb5945.png)


![image](https://user-images.githubusercontent.com/43002915/141303410-11af36ce-d4e8-4065-9346-4b4b4a1651bb.png)
