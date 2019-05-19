# ballista
Python based library to load data from multiple data sources to snowflake
Features :

1) Configuration based setup to load data from various sources including Oracle, MongoDB, Cassandra etc.
2) Multinode cluster based distributed architechture.
3) Horizontally scalabale to increase load capacity and speed as needed.
4) Smart delta load to minimize db operations while keeping data in sync.
5) Auto-recovery mechanism on failure on jobs.
6) Notification system for all kinds of events (SUCCESS/FAILURE).
7) Heartbeat check of all the connected nodes in the cluster.
8) Auto redistribution of jobs in case of node failure.
