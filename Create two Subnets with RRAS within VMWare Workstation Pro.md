**FIRST VM - WINDOWS 10**

![5a95139d87f829d72b5885e3cd2fd355.png](http://localhost:9425/images/019f8f98-8e9c-76ca-8c69-c5c982e1eb4b.png)

**SECOND VM - WINDOWS 10**

![ffba606b9ae9fbe5f34d516399b52844.png](http://localhost:9425/images/019f8f98-8ea1-770d-b863-b16e87143836.png)

**THIRD VM- WINDOWS SERVER 2022 (RRAS)**

![f52fa0d756484352cb2ac2970d00254f.png](http://localhost:9425/images/019f8f98-8ea7-71ff-897c-b3e6f95b1f09.png)

* * *

**FIRST VM NETWORK CONFIGURATION**

Static IP: 192.168.10.10

Subnet: 255.255.255.0

Gateway: 192.168.10.1 (RRAS - Windows server 2022)

DNS: 127.0.0.1

**SECOND VM NETWORK CONFIGURATION**

Static IP: 192.168.20.10

Subnet: 255.255.255.0

Gateway: 192.168.20.1 (RRAS - Windows server 2022)

DNS: 127.0.0.1

**NETWORK CONFIGURATION ON RRAS**

Screenshot below for first VM

![cd17368cf50770652455b9f5f1c762f1.png](http://localhost:9425/images/019f8f98-8eab-736f-a0c1-b28389df4687.png)

Screenshot below for second VM

![7f740fcd69ab4d008087e04fef10fe3a.png](http://localhost:9425/images/019f8f98-8ead-76a0-9cba-a746a60a8616.png)

Third network configuration is for NAT (internet access for 1st and 2nd VMs)

![c96d20dd0fd46c57621a0a2b97a07390.png](http://localhost:9425/images/019f8f98-8eb1-761c-827d-7970e0fe1fbc.png)

Then enable RRAS on Windows server 2022 and configure as seen in screenshot below, choosing NAT and internal Routing option.

Screenshot below is Internal Routing

![6b75981da4fcef028350af16ecc50182.png](http://localhost:9425/images/019f8f98-8eb4-77cf-9180-e5bdf1cfb794.png)