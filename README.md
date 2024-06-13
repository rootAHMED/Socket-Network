# Tested on a real Ubuntu Server

## ![Mesh-Network-Topology-Type](https://github.com/rootAHMED/Socket-Network/assets/102583986/c1f8f488-0ace-44bc-87be-56f7c3228a21)

### `step 1`
### Once we open port 1234, we'll be able to listen
```
sudo apt-get update
sudo apt-get install ufw
```
```
sudo ufw enable
```
```
sudo ufw allow 1234/tcp
```
```
sudo ufw allow 1234/tcp
```
```
sudo ufw reload
```

### ` step 2 `

The server starts listening.

![image](https://github.com/rootAHMED/Socket-Network/assets/102583986/c7de3957-4d95-4098-aa46-6679f0e412fb)


### ` step 3 `

The client sends a Hello message and the server receives it

![Screenshot 2024-06-13 101653](https://github.com/rootAHMED/Socket-Network/assets/102583986/3eccc4b1-fa6c-4ee7-ad40-de73e83ee0a6)


### `step 4`

After all this, we will inspect the logs using the Snort tool
#### ![snort](https://github.com/rootAHMED/Socket-Network/assets/102583986/ec8afbde-55bb-4478-a2e0-907486680b72)

``Snort is a widely-used open-source network intrusion detection and prevention system (IDS/IPS) created by Martin Roesch. It helps detect and respond to suspicious activities on computer networks.``

![image1](https://github.com/rootAHMED/Socket-Network/assets/102583986/d17f2f61-6e92-4dfa-8a03-3fae3d7556cf)

### resource:
https://www.linuxhowtos.org/C_C++/socket.htm

https://www.geeksforgeeks.org/socket-programming-cc/

https://www.amazon.com/Unix-Network-Programming-Volume-2nd/dp/013490012X
