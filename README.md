# Network-Design-for-Smart-Home

## Smart Home Network Diagram
![image](https://user-images.githubusercontent.com/51742771/144625771-f6d9087e-a7b8-4a0e-8ec5-eaabc8484219.png)

## Components of Smart Home
* IoT Smart Devices like Lamps, Windows, Fans, Motion Detector, etc. which
can be accessed via the internet using smartphones, laptops and tablets.
* Cable modem connects to the internet
* Home gateway it connects the home network to WAN
* Switches transfer data on a network to other devices of a given network
* Central office server connects the home server to office server and there by
connects all the devices and performs remote controlling.
* DNS servers are translating the ip address to domain name and exchanging the
counter parts too
* IoT servers which maintain the data integration ,storage and collection part from
the servers and maintain integration

## Network Design
* According to the diagram our architecture is divided into three clusters namely
Smart home environment, remote environment and Internet cloud
* The smart home environment is where all the IOT devices, sensors, Lan
management and the home gateway are present and connected to the servers
which makes a simple network of smart devices.
* The second cluster is the remote environment which is established to access the smart home environment i.e., the
smart home appliances via smartphones, laptops or tablets remotely from
anywhere which is connected through internet.
* The third cluster mentioned is the Internet cloud. All the connections between
the smart home environment and the remote environment are established
through the internet cloud. It is basically the internet service provider to the
whole network. All the data related to the IOT network; smart home network is
stored in the server database in the internet cloud
