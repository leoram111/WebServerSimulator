# WebServerSimulator
This application can be used to bring up up to 1000 SimpleHTTPWebservers within a minute.  
This is helpful in case of large scale horizontal scalability testing environments.  
Run: 
Use cmd line argument to provide the port number or port range as below 
1. (./WSSimulator 8000) or (./WSSimulator 8000 8999) 
2. (./WSSimulator 8000 8999 443) or (./WSSimulator 8000 8999 443 480) 
3. (./WSSimulator 8000 8999 443 480 9000) or (./WSSimulator 8000 8999 443 480 9000 9005) 
Here 8000 is the start port and 8999 is the end port for HTTP Here 443 is the start port and 480 is the end port for HTTPS Here 9000 is the start port and 9005 is the end port for WebSocket.
4. Enter ports as 0 to not start those webservers(./WSSimulator 8000 8999 0 0 9000 9005). This will not start ssl webservers.
