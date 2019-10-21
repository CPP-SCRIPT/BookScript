# Packets

**Packets** are segments of data passed through networks :

1.5 Kbs over ethernet usually 

64 KBs in IP Packets

![Structure of a Packet](../../.gitbook/assets/packet-structure.png)

## Packet Switching

Most of the packet switching uses a method called **Store-and-forward transmission**

**Store-and-forward transmission ::**  the packet switch must receive the entire packet before it can begin to transmit the first bit of the packet onto the outbound link.

Example: 

Lets have a **Packet** be **L bits.**

Lets have the Rate, **R** bits/seconds

So the time to transmit the packets is **L/R seconds.**

![](../../.gitbook/assets/image%20%282%29.png)

\*\*\*\*

From the **source** to the **router** is **L/R.** From the **router** to **destination** is **L/R.** So at **2L/R** the first packet has been received and the second packet has been sent to the router. Amount of packets + number of routers in the middle = **N.**

So for all the packets to be received : 

where **N** is the amount of links. 

![](../../.gitbook/assets/image%20%283%29.png)

