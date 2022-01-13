- **OSI Model** - The open systems Interconnection model is a reference model that describes how applications interact with each other over a computer network. <br />
The OSI Model has 7 layers:- 
Physical → DataLink → Network → Transport →  Session → Presentation → Application.<br />
- **Physical** - This is the lowest level of the OSI Model. Here, data is converted into an electrical impulse so that it can be sent through a physical medium. It is also responsible for the physical connection between the devices.<br />
- **Datalink**- Data packet is encoded and decoded into bits.<br />
- **Network** - The function of this layer is routing and logical addressing.<br />
- **Transport** - This layer is responsible for end-to-end connections. The data in this layer are called segments.<br />
- **Session** -  This layer controls signals between computers. It establishes, maintains, and terminates connections between processes.<br />
- **Presentation** -  It is responsible to translate data into the application layer format. The data is formatted, encrypted and then sent to the next layer.<br />
- **Application** - Services are provided to the end-user.When the data is transmitted over a network it can be transmitted in either of these three manners:<br />
- **Unicast** - Information is sent from a single user to a single receiver. (Point to Point Communication). <br />
- **Multicast** - Data is sent from 1 or more sources to multiple destinations. ( IGMP to identify groups)<br />
- **Broadcast** - It is known as one to all. Communication is between a single user and multiple receivers. <br />
- **DNS** - Domain name system. Responsible for mapping the domain to a corresponding IP address. <br />

### Types Of Networks

| SL  | Type                                        |Description                                                                                                                 |
| --- | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------- |
| 1   | PAN (Personal Area Network) | Let devices connect and communicate over the range of a person. E.g. connecting Bluetooth devices. |
| 2   | LAN (Local Area Network) | It is a privately owned network that operates within and nearby a single building like a home, office, or factory. |
| 3   | MAN (Metropolitan Area Network) | It connects and covers the whole city. E.g. TV Cable connection over the city. |
| 4   | WAN (Wide Area Network) | It spans a large geographical area, often a country or continent. The Internet is the largest WAN. |
| 5   | GAN (Global Area Network) | It is also known as the Internet which connects the globe using satellites. The Internet is also called the Network of WANs. |



### Difference between OSI Reference Model & TCP/IP Reference Model

| SL  |OSI Reference Model	   | TCP/IP Reference Model |
| --- | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------- |
| 1   | 7 layered architecture | 4 layered architecture |
| 2   | Fixed boundaries and functionality for each layer | Flexible architecture with no strict boundaries between layers |
| 3   | Low Reliability | High Reliability |
| 4   | Vertical Layer Approach | Horizontal Layer Approach |
| 5   | [OSI Model Architecture](https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/381/original/Layers_of_OSI_Model.png?1619607169) | [TCP/IP Model Architecture](https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/382/original/Layers_of_TCP_IP.png?1619607553) |


### Difference between TCP & UDP


| SL  |TCP/IP   | UDP |
| --- | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------- |
| 1   | Connection-Oriented Protocol	 | Connectionless Protocole |
| 2   | More Reliable | Less Reliable |
| 3   | Slower Transmission | Faster Transmission |
| 4   | Packets order can be preserved or can be rearranged | Packets order is not fixed and packets are independent of each other |
| 5   | Uses three ways handshake model for connection | No handshake for establishing the connection |
| 6   | Protocols like HTTP, FTP, Telnet, SMTP, HTTPS, etc use TCP at the transport layer | Protocols like DNS, RIP, SNMP, RTP, BOOTP, TFTP, NIP, etc use UDP at the transport layer |