# OSPF – Open Shortest Path First

- It is an Interior Gateway Protocol (IGP).
- It is based on dividing the network into areas. An area consists of the nodes and routers that are logically divided into several groups.
- It is based on router ID and router priority.

## Configuring the routers using OSPF protocol

We need to logically divide the areas by adding the addresses of the network interfaces that the router is directly connected to along with the area number. We shall use the CLI to do the configurations.

### Syntax
```network <ip addr> <wildcard mask> area <area num>```

### Wildcard mask – Subnet mask is inverted to obtain wildcard mask

- IP Address = 192.168.1.0
- Subnet mask = 255.255.255.0 (11111111.11111111.11111111.00000000)
- Wildcard mask = 0.0.0.255 (00000000.00000000.00000000.11111111)

- IP Address = 12.1.1.0
- Subnet mask = 255.0.0.0 (11111111.00000000.00000000.00000000)
- Wildcard mask = 0.255.255.255 (00000000.11111111.11111111.11111111)

### Configuring Router0 by creating router OSPF 1 and then add IP address along with wildcard mask of networks that the router is directly connected to.

![image](https://github.com/user-attachments/assets/6b0d5645-031a-43e5-894e-f72fa4d6f205)

### Configuring Router1 by creating router OSPF 1 and then add IP address along with wildcard mask of networks that the router is directly connected to.

![image](https://github.com/user-attachments/assets/9e7ebbb8-4b0e-4fb3-bc74-e628a844aef0)

### Configuring Router2 by creating router OSPF 1 and then add IP address along with wildcard mask of networks that the router is directly connected to.

![image](https://github.com/user-attachments/assets/a191f932-7e7b-4850-8271-4a0f6d7295aa)

### Testing the connections

![image](https://github.com/user-attachments/assets/09f0c118-20fc-4ba7-a733-02277ed708f5)
![image](https://github.com/user-attachments/assets/599a849b-0693-4bfc-88aa-3774c2729f86)






