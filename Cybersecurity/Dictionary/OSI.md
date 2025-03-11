The **OSI** (Open Systems Interconnection) Model is a conceptual framework that describes how data communication occurs between devices in a network. It consists of seven layers, each with specific functions:

1. **Physical**: Deals with physical transmission media
2. **Data Link**: Handles error-free transfer between adjacent nodes
3. **Network**: Manages addressing and routing
4. **Transport**: Ensures end-to-end data delivery and flow control
5. **Session**: Establishes, manages, and terminates connections
6. **Presentation**: Formats and encrypts data for the application layer
7. **Application**: Provides network services to end-user applications

More detailed info about layers:
1. **Layer 1 - Physical Layer**: The first layer enables physical connection between the two network devices. It facilitates data transmission in bits while managing bit rate control,  cabling or wireless technology, voltage, and topography, among other things.
2. **Layer 2 - Data Link Layer**: Two physically connected nodes on a network require a connection. The data link layer helps create and terminate a connection by breaking up packets into frames and transmitting them from source to destination. This layer fixes problems generated due to damaged, duplicate, or lost frames.
3. **Layer 3 - Network Layer**: This layer fulfills two primary functions. The first function consists of splitting up segments into network packets and putting the packets back together at the receiver’s end. The second ensures the transmission of packets across the physical network via the most optimal route.
4. **Layer 4 - Transport Layer**: Data incoming in its raw state from the preceding layer is broken into “segments” and is reassembled on the receiving end at the transport layer. This layer manages the flow control by transmitting data to match the receiving device’s connection speed and monitors error control by ensuring that the received data is correct.
5. **Layer 5 - Session Layer**: This layer establishes a communication channel called a session between the devices that want to exchange data. The session layer opens sessions and ensures they function effectively during data transmission and closes the respective sessions once the communication ends.
6. **Layer 6 - Presentation Layer**: This layer arranges data for the application layer by ensuring the correct representation concerning information syntax and semantics. It also controls file-level security by defining how the connected devices should encrypt and compress data to provide accurate data transmission at the receiver’s end.
7. **Layer 7 - Application Layer**: The top layer of the network, the application layer, is accessed by end-user software such as web browsers and email clients. Protocols at this layer allow applications to send and receive information and present easy-to-understand and relevant data to users.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/OSI_Model_v1.svg/1200px-OSI_Model_v1.svg.png)