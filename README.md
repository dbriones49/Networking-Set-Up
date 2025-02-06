# Networking-Set-Up
 Router - Switch - PC Configuration


## Introduction

In this networking project, I am designing and configuring a simulated network environment. Utilizing Cisco Packet Tracer, a powerful network simulation tool, I will demonstrate the functionality and interconnectivity of basic network devices, including switches for local traffic management and a router for directing traffic between different networks. This project aims to showcase the essential skills required for network configuration and management in a controlled setting.

The network will consist of three switches, one router, and six PCs, with each device configured through a Command Line Interface (CLI) to ensure precision and a deeper understanding of networking principles. By using CLI, I will gain hands-on experience in executing commands and troubleshooting potential issues within the network.

Understanding how to configure network devices in a real-world environment is crucial for any business, as it ensures efficient communication and data transfer across the organization. Moreover, the quality of configurations directly impacts network performance, security, and reliability, making it imperative for IT professionals to master these skills. 


## Design

I am choosing the 2911 Router, as it allows for 3 different GB connections. Switches were added and the PCs, were re-labled to reflect a sequential order. Copper straight throw cable will be used to connect the PCs to the switch, using Fastethernet0. Gigethernet will be used to connect the switches to the router.



![image](https://github.com/user-attachments/assets/ccd6e97e-9dd3-4d1e-b25d-fb5688b62405)


## Router -Switch Configuration

Settings in the router and switches now need to be configured.


![image](https://github.com/user-attachments/assets/d7d130c0-837c-4316-b64d-723e3e4dc79b)

We begin with typing "enter", then "confirm terminal". 
Next we set up the gigabyte cable by entering " interface g0/0.
To set up the IP address, we enter " ip address 1.0.1.1. 255.255.255.0
Next we enter "no shutdown".
Finally, we hit enter, then enter "exit".

We repeat the steps to configure the next switch.

![image](https://github.com/user-attachments/assets/88349fcf-2a5a-4ca1-b970-3365db01e4fa)


Once completed, the green arrows confirm the configurations are correct.


![image](https://github.com/user-attachments/assets/4773be5f-1ed1-47ad-9237-09471c6a7b5b)


## PC configuration

We begin opening up PC1 and going to IP configuration under desktop. We enter the IP address of the PC, enter the subnet mask, and ensure the default gateway's IP address matches that of the switch. From here, we repeat the configuration process for the 
remainder of the PCs. It is important to configure the PCs tied to the 2nd switch, to reflect matching subnets and Gateways.

![image](https://github.com/user-attachments/assets/7965098f-cfc5-40c3-9c2e-eb3ecf9e0195)



![image](https://github.com/user-attachments/assets/4d73c1e3-9992-4de6-a862-aaf3d49846e6)


## Testing the connections

By using the Realtime feature and by opening up PC's terminal, we can attempt to ping PC 1and PC 3. The terminal reflects the communication attempts were successful.









![image](https://github.com/user-attachments/assets/5f52f3a1-33c3-491f-a45b-ee148c3380dd)


# Additional devices

From here we can simple repeat the process to configure the third switch and last two PCs. 








![image](https://github.com/user-attachments/assets/adb15aad-c454-4b56-87c4-a092aec06ee0)










We complete a final ping to last two PCS, and confirm the connections are successful.

![image](https://github.com/user-attachments/assets/9a4df231-9f5c-4c78-8669-d90a898a9303)



![image](https://github.com/user-attachments/assets/b4ecf30b-c59b-4385-a1b1-d8121e3c1309)

## Conclusion

Understanding basic IT networking fundamentals is crucial for effectively configuring switches, routers, and PCs, as it provides the foundational knowledge of how data flows across networks. This knowledge enables IT professionals to design and troubleshoot networks efficiently, ensuring optimal performance and security. Furthermore, a solid grasp of networking principles helps in implementing best practices and standards, which are vital for maintaining reliable communication and connectivity within an organization.

 
