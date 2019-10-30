# Network

Networks is an important part of cyber security. It is the way that communications between computers are connected and utilizing this communication can be used for nefarious purposes.

## OSI Model



![OSI Model](../../.gitbook/assets/help.jpg)

### Application Layer

     The application layer is the only layer that is closest to the end user.  POST requests and GET Requests. Usually **plaintext.** 

     ****ex: HTTP, DNS, FTP, SSH

### Presentation Layer

     This layer is responsible for the translation, encryption, and compression of data. Essentially this is the layer in which the information is transformed to have some type of encryption. Sending data in networks heavily involve this layer.

     ex. MPEG, AES, SSH, SSL

### Session Layer

     Responsible for opening the networking session to then send data over. 

     ex: Sockets, Winsock

### Transport Layer

   Takes the information from the **Session Layer** and transforms it into segments so that it can be sent out and put into different categories to be sent out. It also looks at the error flow and tries to assimilate the data that it receives so that it will be usable for the **Session Layer.**

     ****ex. TCP, UDP

### **Network Layer**

     ****Responsible for routing and for packet creation and assembly. 

     ex. IP, ICMP

### Data Link Layer

     If two devices are on the same network then it will take the packets created in the Network layer and take it a step further and split it up into frames. It is also responsible for error handling and flow control

     ex. Ethernet, Switch, Bridge

### Physical Layer

     Frames get converted into binary and get sent through the medium.

     ex. wires, wireless, fiber, coax, bluetooth

\*\*\*\*

    









