Swarm AWS Security Group
========================
The following ports must be available

Inbound Traffic for Swarm Management
------------------------------------
- TCP port 2377 for cluster management communications
- TCP and UDP port 7946 for communication among nodes
- UDP port 4789 for overlay network traffic

Inbound Traffic for Swarm Workers
---------------------------------
- TCP and UDP port 7946 for communication among nodes
- UDP port 4789 for overlay network traffic
