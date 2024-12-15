Router 1941
Switch0 (2960-24TT)
Switch1 (2960-24TT)
PC0 (PC-PT) 168.90.02
PC1 (PC-PT) 168.90.03
Laptop0 (Laptop-PT) 168.90.04
Server0 (Server-PT) 168.90.05
Server1 (Server-PT) 210.3.14.2
Server2 (Server-PT) 210.3.14.3
PC2 (PC-PT) 210.3.14.4
For Switch 1 (168.90.0.0/16 network)
Created a DHCP pool named `Switch1_Pool`.
Set the default gateway as `168.90.0.1` and the subnet mask as `255.255.0.0`.
The range of IP addresses assigned to hosts is from `168.90.0.2` to `168.90.255.254`.

For Switch 2 (210.3.14.0/24 network)
Created a DHCP pool named `Switch2_Pool`.
Set the default gateway as `210.3.14.1` and the subnet mask as `255.255.255.0`.
The range of IP addresses assigned to hosts is from `210.3.14.2` to `210.3.14.254`.
