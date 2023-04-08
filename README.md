
# :rice_ball: Computer Networks, SDN, Mininet, Python, Linux and a little bit of everything :rice_ball:

:lollipop:*Normally this repo started because of my computer engineering thesis on software defined networking and mininet but i didn't found much that statifed me when i was a beginner with mininet so i wanted to give my full knowledge and be a stater for using mininet and visualizing sdn through it*:lollipop:

In this repository you will found everything about SDN, Computer networks, Mininet and Python also this repository contains code examples and resources for a software-defined networking (SDN) implemented using Mininet tool.

![image](https://user-images.githubusercontent.com/76471156/230721842-5d17f92f-c1de-4288-8207-e1fe76ae05c1.png)

# :earth_africa: Network Topology Complete Guide :earth_africa:

# :books: The Best Books to Learn How Computer Networks Work :books:
- Computer Networking: A Top-Down Approach by James Kurose, Keith Ross 
- Networking All-in-One For Dummies by Doug Lowe
- Network Programmability and Automation: Skills for the Next-Generation Network Engineer 
- For more books https://www.guru99.com/best-computer-networks-books.html

# What is a network topology?

A network topology is the physical and logical arrangement of nodes and connections in a network. Nodes usually include devices such as switches, routers and software with switch and router features. Network topologies are often represented as a graph.

Network topologies describe the arrangement of networks and the relative location of traffic flows. Administrators can use network topology diagrams to determine the best placements for each node and the optimal path for traffic flow. With a well-defined and planned-out network topology, an organization can more easily locate faults and fix issues, improving its data transfer efficiency.

<p align="center">
    <img  src="https://user-images.githubusercontent.com/76471156/230731189-e29e9b6e-68ba-4911-b43a-12ad45971aa4.png">
</p>



# Types of Network Topology
1. Point-to-Point Topology 
The point-to-point topology is fairly basic, with a pair of nodes interconnected directly via a shared connection. The entire frequency of this connection can be reserved for data transfer between the paired nodes. This type of network connectivity involves a wire or cable to join two ends, but other alternatives such as microwaves and satellite connections are also viable. Since the button is used to change stations, the point-to-point connectivity is mostly created between the Television as well as the remote. Transmission of data over the computer system can be accomplished in numerous ways in this architecture, including half-duplex mode, Simplex mode, and full-duplex mode. 

2. Star Topology 
A star topology allows every node to be configured to the centralized hub, centralized computer, or the connected switches. A server is just a main hub in this context, and the many devices linked to the server are referred to as users. Computers may be linked together via RJ45 wire or coaxial connection. Within this topology, hubs or switches are employed as linked devices. This kind of topology is commonly utilized in network implementation. 

3. Ring Topology 
Except for interconnected endpoints, ring topology is identical to bus topology. Generally, this form of topology is classified as unidirectional or bidirectional. These topologies enable information to go in just one way, resulting in a linear ring topology, whilst others enable information to travel in any manner, resulting in a bidirectional ring topology. Each device in this configuration may be linked by utilizing two or more devices to build a circular channel. Token rings are topologies that allow information to be sent from one machine to another until it reaches its destination. So, when we join multiple computers and other networking devices inside a ring topology structure, the computer system here is referred to as a ring system. 

4. Bus Topology
Any units in a bus topology can be connected using a unified cable with dropped lines. A tap is a mechanism that connects the dropped line to the single connection. This topology may be designed by connecting all of the units with a singular cable known as a backbone cable. Each node could be linked to this singular wire throughout a dropped cable or effectively to this wire. When a node needs to send a message over the platform, it posts a signal on the channel so that all units linked to the system get the information. 

5. Mesh Topology 
Any network device and PC are linked together using a mesh topology. This design enables for many signals to be distributed even if any links fail. This architecture is mostly utilized in wireless systems. The connectivity of networks in this architecture may be done totally to each other using a specialized channel through which information can pass from source node to destination node. If the elements in a mesh are 'M,' so there are M (M-1)/2 interconnections. Each network has a feature such as a point-to-point connectivity to the parallel component. The interconnections in this architecture are often wireless or wired.

In a full mesh topology, the computers in a local area network are interconnected with every other computer in the same network. In a partial mesh topology, not all but few computers are interconnected with other computers to which they communicate constantly. 

6. Tree Topology 
Multiple devices in a tree topology could be linked together like branches. These topologies are widely used to link pcs in a company system. In this topology, there is only one connection between any two linked elements since these two nodes have just one reciprocal link that forms a typical parent and child structure. This sort of topology is also known as a star bus topology in computer systems since it combines the features of a bus and star topology. This type of design is more successful in specific instances, such as communication between two separate networks. The network model necessitates the use of several nodes such as the intermediate, root, and lead.

In a full mesh topology, the computers in a local area network are interconnected with every other computer in the same network. In a partial mesh topology, not all but few computers are interconnected with other computers to which they communicate constantly. 

7. Hybrid Topology 
The hybrid topology is the mixture of two or more node designs such as ring, mesh and bus. The selection and use of this system is mostly determined by the desired network bandwidth, position, and number of machines. To provide a complicated structure, the practical execution of this topology necessitates the use of many technologies. The key advantages of this system are increased versatility, high availability, and the ability to simply modify or add other topologies. This type of structure is more useful when complete variation is required inside the system. Along with its low cost, this system design is employed in a variety of industries. The hybrid topology concept is superior to other essential structures; it may also be configured in various environments. For users to administer, maintain, and construct the organization. 

<p align="center">
    <img  src="https://user-images.githubusercontent.com/76471156/230731468-1c3512dd-46b0-4c4b-857e-bac7ba14b390.png">
</p>


# What is Mininet?


<a href="https://github.com/mininet/mininet">
<img  src="https://readme-components.vercel.app/api?component=logo&fill=black&logo=github" alt="This is the Mininet github repository">
</a>
Mininet is an open-source network emulator that allows you to create a virtual network on a single machine. With Mininet, you can create a network topology of switches, routers, hosts, and other networking devices, and emulate the behavior of a real network by simulating network traffic and protocols.
![image](https://user-images.githubusercontent.com/76471156/230721903-a3247adc-dfef-460c-89cb-0e65e491436f.png)

Mininet is built on top of Linux container technology, which allows it to create isolated network environments that share the same kernel as the host machine. This means that you can create and manage multiple virtual networks on a single physical machine, without needing additional hardware.

Mininet is often used in the development and testing of software-defined networking (SDN) applications and protocols, as it provides a flexible and scalable environment for testing different network configurations and traffic patterns. Additionally, Mininet is widely used in educational settings to teach computer networking concepts and protocols.
You can use mininet with the mininet CLI and Mininet Python API(you need python knowledge for this one) and also with mininet GUI like the photo above and also you need to learn the basics of using linux based operating systems(i use ubuntu 20.04).
### Best Linux distros of 2023
1. Nitrux Best Linux distro for beginners 
2. Zorin OS Best Linux distro for Windows users
3. Arch Linux Best Linux distro for power users
4. Ubuntu (my personal favorite)
For further reading visit https://www.techradar.com/best/best-linux-distros

### How to Install Linux on Windows 10?
- The full guide is here https://www.hellotech.com/guide/for/how-to-install-linux-on-windows-10
- Mininet alternatives https://www.topbestalternatives.com/mininet/
![image](https://user-images.githubusercontent.com/76471156/230730594-34139756-9f2a-4e8d-85ff-1ad08b4ca3a8.png)

### For further reading visit  - [Mininet](http://mininet.org/) 

# How to install and use mininet ?

To install natively from source, first you need to get the source code:
```
git clone https://github.com/mininet/mininet
```
Note that the above git command will check out the latest Mininet verison If you want to run the last tagged/released version of Mininet - or any other version - you may check that version out explicitly:
```
cd mininet
git tag  # list available versions
git checkout -b mininet-2.3.0 2.3.0  # or whatever version you wish to install
cd ..
```
Once you have the source tree, the command to install Mininet is:
```
mininet/util/install.sh [options]
```
Typical install.sh options include:

    -a: install everything that is included in the Mininet VM, including dependencies like Open vSwitch as well the additions like the OpenFlow wireshark dissector and POX. By default these tools will be built in directories created in your home directory.
    -nfv: install Mininet, the OpenFlow reference switch, and Open vSwitch
    -s mydir: use this option before other options to place source/build trees in a specified directory rather than in your home directory.

So, you will probably wish to use one (and only one) of the following commands:
```
To install everything (using your home directory): install.sh -a
To install everything (using another directory for build): install.sh -s mydir -a
To install Mininet + user switch + OvS (using your home dir): install.sh -nfv
To install Mininet + user switch + OvS (using another dir:) install.sh -s mydir -nfv
```
You can find out about other useful options (e.g. installing the OpenFlow wireshark dissector, if it’s not already included in your version of wireshark) using
```
install.sh -h
```
After the installation has completed, test the basic Mininet functionality:
```
sudo mn --switch ovsbr --test pingall
```
And thats all! if you want to install Mİninet from VM or packages visit this link http://mininet.org/download/

# What is SDN?

Software-defined networking (SDN) is an approach to network architecture that aims to make networks more flexible, programmable, and easier to manage. In traditional networking, the control plane (which determines how packets are routed through the network) and the data plane (which forwards packets based on the routing decisions made by the control plane) are tightly integrated within the network devices themselves.

In an SDN architecture, the control plane is separated from the data plane, and a centralized controller is responsible for making routing decisions and configuring the behavior of the network devices. This allows network administrators to program the network using software, rather than having to manually configure each device.

SDN architectures typically use a protocol called OpenFlow to communicate between the controller and the network devices. OpenFlow allows the controller to program the behavior of the network devices, including how they should handle incoming packets, how they should route traffic, and how they should respond to events and failures.

SDN has a number of benefits over traditional networking, including increased flexibility, faster deployment times, easier management and configuration, and improved network security. SDN architectures are increasingly being used in data centers, cloud computing environments, and other large-scale networking applications.

# The terms you need to know about SDN

1. Control plane: The part of the network that makes routing decisions and configures network devices.

2. Data plane: The part of the network that forwards packets based on the routing decisions made by the control plane.

3. OpenFlow: A standardized protocol used to communicate between the control plane and data plane in an SDN architecture.

4. Network functions virtualization (NFV): A technique that involves virtualizing network functions, such as firewalls, load balancers, and intrusion detection systems, and running them on commodity hardware.

5. Northbound interface: An API that allows applications to interact with the SDN controller.

6. Southbound interface: An API that allows the SDN controller to interact with the network devices, such as switches and routers.

7. Controller: The centralized entity in an SDN architecture that manages the network and communicates with the network devices using the southbound interface.

8. Overlay network: A virtual network that is built on top of a physical network, allowing for greater flexibility and control.

9. Underlay network: The physical network infrastructure that supports the overlay network.

10. Virtual switch: A software-based switch that is used to connect virtual machines to each other and to the physical network in a virtualized environment.

11. Network slicing: The technique of dividing a physical network into multiple logical networks, each with its own unique characteristics and requirements.

12. Software-defined WAN (SD-WAN): An SDN-based approach to wide area networking that allows for greater flexibility and control over network traffic.

# Mininet SDN topologies

Mininet supports a variety of network topologies, including:

1. Linear: In a linear topology, the hosts and switches are connected in a linear chain.
2. Tree: In a tree topology, the network is organized like a tree, with a root switch connecting to multiple branches of switches and hosts.
3. Mesh: In a mesh topology, all hosts and switches are connected to each other, creating a fully connected network.
4. Torus: In a torus topology, the network is organized like a torus, with hosts and switches connected in a circular fashion.
5. Fat tree: In a fat tree topology, the network is organized like a tree, but with multiple paths between hosts and switches to provide redundancy and load balancing.
6. Custom: Mininet also allows users to create custom network topologies by specifying the connections between hosts and switches.

The choice of Mininet topology depends on the specific requirements of the network being emulated, such as the number of hosts and switches, the level of redundancy and fault tolerance needed, and the types of traffic patterns and applications that will be running on the network.


# How does Software-Defined Networking (SDN) work?

Here are the SDN basics: In SDN (like anything virtualized), the software is decoupled from the hardware. SDN moves the control plane that determines where to send traffic to software, and leaves the data plane that actually forwards the traffic in the hardware. This allows network administrators who use software-defined networking to program and control the entire network via a single pane of glass instead of on a device by device basis.

There are three parts to a typical SDN architecture, which may be located in different physical locations:

Applications, which communicate resource requests or information about the network as a whole

Controllers, which use the information from applications to decide how to route a data packet

Networking devices, which receive information from the controller about where to move the data

Physical or virtual networking devices actually move the data through the network. In some cases, virtual switches, which may be embedded in either the software or the hardware, take over the responsibilities of physical switches and consolidate their functions into a single, intelligent switch. The switch checks the integrity of both the data packets and their virtual machine destinations and moves the packets along.

### and the most important part is :
# How is SDN different from Traditional Networking?

The key difference between SDN and traditional networking is infrastructure: SDN is software-based, while traditional networking is hardware-based. Because the control plane is software-based, SDN is much more flexible than traditional networking. It allows administrators to control the network, change configuration settings, provision resources, and increase network capacity—all from a centralized user interface, without adding more hardware.

There are also security differences between SDN and traditional networking. Thanks to greater visibility and the ability to define secure pathways, SDN offers better security in many ways. However, because software-defined networks use a centralized controller, securing the controller is crucial to maintaining a secure network, and this single point of failure represents a potential vulnerability of SDN.
### For further reading - [What is Software-Defined Networking (SDN)?](https://www.vmware.com/topics/glossary/content/software-defined-networking.html) 

# Architectural components of SDN

SDN Application: Programs that directly and programmatically communicate their network requirements and desired behavior to the SDN Controller via a northbound interface (NBI).

SDN Controller: A logically centralized entity that translates the requirements from the SDN Application layer down to the SDN Datapaths and provides the SDN Applications with an abstract view of the network.

SDN Datapath: A logical network device that exposes visibility and uncontested control over its advertised forwarding and data processing capabilities.

SDN Control to Data-Plane Interface (CDPI): The interface defined between an SDN Controller and an SDN Datapath, which provides programmatic control of all forwarding operations, capabilities advertisement, statistics reporting, and event notification.

SDN Northbound Interfaces (NBI): Interfaces between SDN Applications and SDN Controllers that provide abstract network views and enable direct expression of network behavior and requirements.

# How SDN handles security in a centralized model risks, challenges and potential solutions?
[Visit for further reading](https://thesai.org/Downloads/Volume10No10/Paper_42-Security_Issues_in_Software_Defined_Networking.pdf) 

# The SDN Architecture
![image](https://user-images.githubusercontent.com/76471156/230720793-02038ce1-e8c6-4481-bb2d-5ff39f6cc1fc.png)

# Recources for reading about SDN
<details>

<summary>Recources for reading about SDN</summary>

### Recources for reading about SDN

- [SDN architecture](https://opennetworking.org/wp-content/uploads/2013/02/TR_SDN_ARCH_1.0_06062014.pdf)
- [Software-defined networking(Wikipedia)](https://en.wikipedia.org/wiki/Software-defined_networking) 
- [Software-defined networking(VMware)](https://www.vmware.com/topics/glossary/content/software-defined-networking.html) 
- [Software-Defined Networking (SDN) Definition](https://opennetworking.org/sdn-definition/) 
- [Software-Defined Networking: A Comprehensive Survey(IEEE)](https://ieeexplore.ieee.org/document/6994333) 
    
</details>

# Resources to learn Python
- The best recource i found in Youtube was https://www.youtube.com/watch?v=eWRfhZUzrAc&ab_channel=freeCodeCamp.org (Python for Beginners – Full Course [Programming Tutorial] by freecodecamp)
- For traning this one was the best https://www.programiz.com/python-programming/examples
# Resources to learn Linux terminal commands
- https://github.com/SaniTheWay/LearnBase-LinuxTerminalCommands
![image](https://user-images.githubusercontent.com/76471156/230732197-e2816198-8970-478f-a9d4-5fbb42579e92.png)

<div align="center">

<img height="120" alt="Thanks for visiting me" width="100%" src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/marquee.svg" />
<br />

![Visitor Count](https://profile-counter.glitch.me/brunnerlivio/count.svg)


<img src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/notepad.gif" alt="Site created with Notepad" height="30" />
<!-- "margin-right: whatever;" -->
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>  
<img src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/ie_logo.gif" alt="Microsoft Internet Explorer" />
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>  
<img src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/noframes.gif" alt="Microsoft Internet Explorer" />

</div>

