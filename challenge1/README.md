3-tier application structure within Microsoft Azure

<img width="624" alt="3Tier" src="https://user-images.githubusercontent.com/51469725/181243659-f50ab5f1-7079-4956-abd4-a849c3148540.png">

For this architecture I have used 4 virtual machines (2 windows, 2 linux) , a public load balancer, internal load balancer, Azure SQL Database , Secondary SQL Database for failover in case the primary goes down.

Arm templates are used for the vm creation.
