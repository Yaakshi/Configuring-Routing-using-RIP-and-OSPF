# RIP – Routing Information Protocol

- It is an intra-domain routing protocol.
- It is based on distance-vector strategy. It means that the shortest route to the destination from source is considered.
- It is based on Dijkstra’s algorithm and link-state algorithm.
- The shortest path is calculated based on the following order:
    - Hop count – number of routers to pass through in order to reach the destination
    - Bandwidth – volume of data that can be sent over connection
    - Priority value
- It is mainly based on the hop count.

### Configuring the routers using RIP protocol

We need to add the addresses of the network interfaces that the router is either directly connected to or indirectly connected to. We can use GUI for configuration.

![image](https://github.com/user-attachments/assets/3fe7fe7e-17f4-4b6e-a76c-1048a6326430)
Click on the router → Config → Routing → RIP → Enter the network address → Click Add

### Testing the connections

![image](https://github.com/user-attachments/assets/d9361268-c095-4c68-84a2-1c2cbf941147)
![image](https://github.com/user-attachments/assets/526f7755-f44c-4ff6-892b-098f356efbfb)
