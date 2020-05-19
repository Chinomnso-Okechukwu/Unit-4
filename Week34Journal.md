## Computer Networks
This is a series of connected computers that can share data and other things among them. It can be as small as just two computers or can be as big as all the computers in a school. 

### History of Computer Networks
Before, computers worked on their own. As they became popular and more accessible to individuals, the need to share resources and data became increasingly important. It is more cost-effective to have computer networks because of the shared resources.
The small networks that emerged in the mid to late 1900's were called Local Area Network(LAN).
The Internet is the biggest computer network we have.

### Ethernet
The most famous and successful LAN was Ethernet. The simplest form of Ethernet consists of computers connected by an ethernet cable. Data is transmitted among these computers through the cable in the form of electrical signals. The first problem with Ethernet was when trying to trasmit data to a single computer, all other computers in that network also receive the electrical signals(data)and they are not sure whether it was intended for them. To solve this problem, each computer in the network was assigned a unique Media Access Control (MAC) address so that when the data is sent they only recieve or accept data that has their MAC address. 

### Carrrier
A shared transmission medium that carries data. For example, air carrying radio waves for wifi.
Using a shared carrier has a big limitation, heavy network traffic. When network traffic is light, the computers can pause for a moment and wait for the traffic on the carrier to clear so they can transmit their data. But even when the traffic subsides, there is a probalility that more than computer that have been waiting for the silence try to transmit their data simultaneously. This will just lead to collisions over and over again.

### Bandwith
The rate at which a carrier can transmit its data.

### Collision Domain
The act of shrinking the amount of devices on a single shared carrier.

### Routing
Creating the paths for transmitting data from one location to another in a network or between networks.

### Message Switching
The transmission of data in which a message is sent as a whole from one location to another through various stops(intermediate nodes). At these nodes, the data is stored then forwarded to the next intermediate node until it reaches its final destination. Each intermediate node knows the next intermediate node to transmit the data to. Message switching uses different routes(intermediate nodes) which reduces traffic congestion over networks.

### Hop and Hop Count
A hop occurs when a data packet is sent from one intermediate node to the other. The number of hops data takes along its route. The total number of intermediate devices such as routers through which a given piece of data must pass between the source and destination, instead of flowing directly over a single wire. Along the data path, each router forms a hop, with data moving from one source to another. It is stored with the message and updated along its journey.

### Hop Limit
The limit on the number of hops a packet can have before it is discarded.

### Packets and Packet Switching
Small pieces of big transmissions. Packet Switching is the chopping up of data into small packets and transmitting these packets along flexible, different routes depending on what route is optimum for that packet, and reassembling these packets to form the whole data at the destination. First packet switching network was called the ARPANET. 

### Internet Protocol
Every computer connect to the internet network has an IP address. TCIP/IP prevents the packets that took different routes from arriving at the same destination in the wrong order. 

### Latency
The delay before a transfer of data begins following an instruction for its transfer.
