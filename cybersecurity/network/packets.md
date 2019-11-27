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

![](../../.gitbook/assets/image%20%281%29.png)

## HTTP Request Message

ex: 

```text
GET /script/index.html HTTP/1.1
Host: www.cpp.edu
connection: close
user-agent: Google Chrome
Accept-language: en
```

The first line is called the **Request line,**  all other lines are called **Header lines.**

### Request Lines

```text
 Method Field
 URL Field
 HTTP Field
```

The **Method Field** is the field that can take in the methods such as GET, POST, HEAD, etc.

The **URL Field** is the field that asks the host what it wants

The **HTTP Field** is the field of the version of HTTP

### Header Lines

The **Host** line is self explanatory, it is the host

The **Connection: close** line states that it doesn't want a persistent connection

The **User-agent** is the browser one uses such as Google Chrome, Mozilla Firefox, Safari, etc.

The **Accept-language** is the language of the packet.

## HTTP Response Message

ex:

```text

```





