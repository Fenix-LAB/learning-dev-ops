# Net

This file is about the network in TI.

## Network
Is a group of computers and other devices connected to each other to share information and resources.

## OSI Model
The OSI model is a conceptual model that characterizes and standardizes the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology. (OSI - Open Systems Interconnection)

- Layer 7: Application: Data is presented to the user or application. (HTTP, FTP)
- Layer 6: Presentation: Data is translated, compressed, or encrypted. (SSL, TLS)
- Layer 5: Session: Communication between devices is established, maintained, and terminated. (SMB, RPC)
- Layer 4: Transport: Data is divided into segments and reassembled into data streams. (TCP, UDP)
- Layer 3: Network: Data is addressed and routed between devices. (IP)
- Layer 2: Data Link: Data is framed and organized into frames. (MAC)
- Layer 1: Physical: Data is transmitted and received. (bits)

## Classifications
- LAN (Local Area Network): A network that connects computers and devices in a limited geographical area such as a home, school, office building, or closely positioned group of buildings.
- WAN (Wide Area Network): A network that connects computers and devices over a wide geographical area, such as a country or the world.
- MAN (Metropolitan Area Network): A network that connects computers and devices in a geographical area or region larger than that covered by even a large local area network but smaller than the area covered by a wide area network.
- CAN (Campus Area Network): A network that connects two or more LANs but is limited to a specific and contiguous geographical area, such as a college campus, industrial complex, or military base.
- PAN (Personal Area Network): A network that connects devices in close proximity to an individual person, typically within 10 meters.

## Devices
- Switches: A network switch is a computer networking device that connects devices together on a computer network by using packet switching to forward data to the destination device.
- Routers: A router is a networking device that forwards data packets between computer networks. Routers perform the traffic directing functions on the Internet.
- Modems: A modem is a device that provides access to the Internet. The modem connects to your ISP, which typically provides either cable or DSL Internet service.

## IP
The Internet Protocol (IP) is the principal communications protocol in the Internet protocol suite for relaying datagrams across network boundaries. Its routing function enables internetworking, and essentially establishes the Internet.

IPv4: 32 bits
IPv6: 128 bits

IP Address: A unique string of numbers separated by periods that identifies each computer using the Internet Protocol to communicate over a network.

IP public: A public IP address is an IP address that can be accessed over the Internet. Like postal address used to deliver a postal mail to your home, a public IP address is the globally unique IP address assigned to a computing device.

IP private: A private IP address is an IP address that's reserved for internal use behind a router or other Network Address Translation (NAT) device, apart from the public. Private IP addresses are in contrast to public IP addresses, which are public and can't be used within a home or business network.

## Protocols
- TCP (Transmission Control Protocol): A standard that defines how to establish and maintain a network conversation through which application programs can exchange data.
- UDP (User Datagram Protocol): A communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet.

### Ports
A port is a communication endpoint identified by a 16-bit number, commonly known as the port number. A port is always associated with an IP address of a host and the protocol type of the communication. It completes the destination or origination network address of a message.

- Well-known ports: 0 to 1023
- Registered ports: 1024 to 49151
- Dynamic ports: 49152 to 65535

- 80: HTTP
- 443: HTTPS
- 21: FTP
- 22: SSH
- 23: Telnet
- 25: SMTP
- 53: DNS
- 110: POP3

