# Read Replicas vs Cross region Read Replicas

Read replica are a great way to scale horizontally for high availability in a read-heavy workloads. Lets say you have a database where the traffic request coming to the database are more of read request than write request, creating a read replica database will reduce the workload on the primary database.

Read replicas are copied asynchronously from your primary database, you route queries to the read replica to reduce the workload off a single database.


