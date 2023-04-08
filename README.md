
# SDN Mininet Thesis

This repository contains code examples and resources for a software-defined networking (SDN) implemented using Mininet tool.

# What is Mininet?

Mininet is an open-source network emulator that allows you to create a virtual network on a single machine. With Mininet, you can create a network topology of switches, routers, hosts, and other networking devices, and emulate the behavior of a real network by simulating network traffic and protocols.

Mininet is built on top of Linux container technology, which allows it to create isolated network environments that share the same kernel as the host machine. This means that you can create and manage multiple virtual networks on a single physical machine, without needing additional hardware.

Mininet is often used in the development and testing of software-defined networking (SDN) applications and protocols, as it provides a flexible and scalable environment for testing different network configurations and traffic patterns. Additionally, Mininet is widely used in educational settings to teach computer networking concepts and protocols.
### For further reading visit  - [Mininet](http://mininet.org/) 

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

#The SDN Architecture
