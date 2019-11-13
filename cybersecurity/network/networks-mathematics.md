---
description: Everything in computer science has math
---

# Networks Mathematics

## Delay 

### Packet Switching

_**Transmission Delay :**_ 

     Time taken to put a packet onto link. Time required to put data bits on the wire/communication medium.

```text
Transmission Delay = Data size / bandwidth = (L/B) second
```



_**Propagation Delay :**_

     _****_Time taken by the first bit to travel from sender to receiver end of the link. Time required for bits to reach the destination from the start point.

```text
Propagation delay = distance/transmission speed = d/s
```



_**Queuing Delay :**_ 

     _****_ Queuing delay is the time a job waits in a queue until it can be executed. It depends on congestion. It is the time difference between when the packet arrived Destination and when the packet data was processed or executed. 

```text
Average Queuing delay = (N-1)L/(2*R)
N =  # of packets
L = size of packet
R = bandwidth
```

 _****_

_**Processing Delay :**_ 

  _****_Delay to process the packets that are given. Usually given in most problems

 _**End to End delay:**_ 

     Add every delay

## Throughput

Assume you have a File and it contains _**F Bits.**_

Assume it takes _**T Time**_ to transfer all of the files.

```text
Average Throughtput = F/T
```

## Round Trip Time

The time it takes to have a packet send from client to server and back to client. 

### Three- Way Handshake

Involved in this is a **three-way handshake.**

```text
The client sends a small packet to the server
The server then sends a small packet to the client
The client then sends a small packet to the server saying that it got it
```

     ****After the **three-way handshake** is established then the object is sent to the server to be sent 

This then takes 2 **RTT**

