# How websites work

Assume you have this URL

```text
www.cpp.edu/script/file.index
```

and in the file index you have images, javascript, and the actual HTML page.

1. The HTTP client creates a TCP connection to www.cpp.edu on port 80. Port 80 is the HTTP port by default. At this time a socket client and socket server are there as well. 

    2. The client then sends an HTTP request for the /script/file.index to www.cpp.edu.

    3. 



