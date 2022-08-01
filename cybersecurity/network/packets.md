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
HTTP/1.1 200 OK
Connection: close
Date: Tue, 31 Dec 2019 15:44:04 GMT
Server: Apache/2.2.3 (CentOS)
Last-Modified: Tue, 31 Dec 2019 15:11:03 GMT
Content-Length: 6821
Content-Type: text/html
```

A response method has 3 main parts to it: a **status line**, six **header lines**, and the **body**

The **status line** has 3 main parts: the protocol version field, the status code, and the corresponding status message

In the **status line** example the protocol version is HTTP/1.1 and the status code is 200 and everything is OK

Some example status codes are

200: everything is OK

301: Moved Permanently

400: Bad Request

404: Not Found

505: HTTP not supported

If you want to try this on your own type this into your terminal \(Linux\)

```text
telnet cis.poly.edu 80 
GET /~ross/ HTTP/1.1 
Host: cis.poly.edu
```

### Header Lines

Now the header lines are very similar to the HTTP Request Message

The **Connection: close** line states that it doesn't want a persistent connection

The **Date** is when the HTTP response was created

The **Server** is the type of server that it is sending to

The **Last-Modified** field is self explanatory

The **Content Length** is the amount of **bytes** that the message entails

The **Content-Type** is the type of message that is being sent





