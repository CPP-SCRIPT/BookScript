# How websites work

Assume you have this URL

```text
www.cpp.edu/script/file.index
```

and in the file index you have images, javascript, and the actual HTML page.

1. The HTTP client creates a TCP connection to www.cpp.edu on port 80. Port 80 is the HTTP port by default. At this time a socket client and socket server are there as well. 

    2. The client then sends an HTTP request for the /script/file.index to www.cpp.edu.

    3. The HTTP server receives the request and finds the object /script/file.index. Then it encapsulates the object in an HTTP response method and sends the response over TCP.

    4. The HTTP server tells the TCP connection to close.

    5. The client sees that the encapsulated message is HTML and then extracts what it can.

NOTE: The HTTP connection itself does not run anything that is being transferred it only sends and receives. 



