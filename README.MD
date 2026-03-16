
> *This project has been created as part of the 42 curriculum by **kqueiroz***

---

# NetPractice

This project is a hands-on exercise designed to introduce the basic concepts of computer networks. In it, we learn how to configure IP addresses, connect devices via a router, and understand the role of a gateway in a network.

## Description
The internet is a network of interconnected computers that enables the exchange of information between devices around the world.
This communication is made possible by a set of protocols that determine how data should be organized, sent, and received, ensuring that the exchange takes place efficiently and securely. Without these rules, computers would be unable to understand or process each other’s information.

#### TCP/IP Protocol
The Internet Protocol (IP) is the method used to send data from one device to another over the internet. Each device has an IP address that uniquely identifies it and allows it to communicate and exchange data with other devices connected to the internet.

The Transmission Control Protocol (TCP) is a communication standard that allows application programs and computing devices to exchange messages over a network. It is designed to send packets over the internet and ensure the successful delivery of data and messages across networks.

TCP and IP are independent protocols that work together to ensure that data is delivered to its intended destination within a network. IP obtains and defines the address—the IP address—of the application or device to which the data should be sent. TCP is then responsible for transporting and routing data through the network architecture and ensuring that it is delivered to the destination application or device defined by IP.

#### Subnet Mask
A subnet mask is a 32-bit number, similar to an IP address (e.g., 255.255.255.0), used in IPv4 to divide a large network into smaller, more manageable subnets. It divides the IP address into two parts: one that identifies the network (or subnet) and another that identifies the specific host.

#### Routers e Switches
Switches facilitate resource sharing by connecting all devices—including computers, printers, and servers—within a small business network. Thanks to the switch, these connected devices can share information and communicate with one another.

Like a switch, a router connects multiple devices to create a network. In addition, a router connects multiple switches and their respective networks to form an even larger network. These networks can be located in a single location or across multiple locations.

> A router acts as a distributor, directing traffic and choosing the most efficient route for information in the form of data packets to travel across the network.

## Instructions
### Running the training interface
1. Download the NetPractice project from the 42 platform.
2. Open the file index.html in your web browser.
3. Enter your 42 login (or start directly if allowed).
4. Select a level and configure the network.
5. Adjust IP addresses, subnet masks, and gateways until all goals are validated.

When a level is successfully completed, a button appears allowing you to move to the next level.

### Exporting configurations
After completing each level:

- Before moving to the next level, export your configuration using the "Get my config" button.
- A configuration file will be downloaded.
- Do not modify the content of the exported file.
- Place the file at the root of your Git repository.

## Resources
- [Tutorial TCP/IP - Júlio Battisti](https://www.juliobattisti.com.br/artigos/windows/tcpip_p1.asp);
- [Crash Course: Computer Networks](https://www.youtube.com/watch?v=3QhU9jd03a0);
- PowerCert Animated Videos:
    - [Modem vs Router - What's the difference?](https://www.youtube.com/watch?v=Mad4kQ5835Y);
    - [Hub, Switch, & Router - What's the difference?](https://www.youtube.com/watch?v=1z0ULvg_pW8);
- [What is a subnet?](https://www.cloudflare.com/pt-br/learning/network-layer/what-is-a-subnet/).