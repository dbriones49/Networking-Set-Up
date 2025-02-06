# Networking-Set-Up
 Router - Switch - PC Configuration


## Introduction

In this networking project, I am designing and configuring a simulated network environment. Utilizing Cisco Packet Tracer, a powerful network simulation tool, I will demonstrate the functionality and interconnectivity of basic network devices, including switches for local traffic management and a router for directing traffic between different networks. This project aims to showcase the essential skills required for network configuration and management in a controlled setting.

The network will consist of three switches, one router, and six PCs, with each device configured through a Command Line Interface (CLI) to ensure precision and a deeper understanding of networking principles. By using CLI, I will gain hands-on experience in executing commands and troubleshooting potential issues within the network.

Understanding how to configure network devices in a real-world environment is crucial for any business, as it ensures efficient communication and data transfer across the organization. Moreover, the quality of configurations directly impacts network performance, security, and reliability, making it imperative for IT professionals to master these skills. 


## Design

I am chosing the 2911 Router, as it allows for 3 different GB connections. Switches were added and the PCs were re labled to reflect a sequential order. Copper straight throw cable will be used to connect the PCs to the switch, using Fastethernet0. Gigehhernet will be used to connect the switches to the router.



![image](https://github.com/user-attachments/assets/ccd6e97e-9dd3-4d1e-b25d-fb5688b62405)


## Configuration

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




 
