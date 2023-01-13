# WebOps

## Networking Fundamentals

### OSI Model

- Describe the OSI model
- Explain how knowing the layer of a problem helps to find a root cause of a network/http problem?

### Layer 3 - Subnets

- Describe what IPv4 address is and what it is used for
- Describe what a subnet is and what is used for
- Explain the CIDR blocks and give example for min/max IP and the number of IPs 
- What subnets are officially private?
- What can private subnets be used for?

### Layer 4 - TCP

- What is ports and what are they used for
- How many ports
- What is a TCP router?

### Web in OSI

- What OSI layers is needed for DNS/HTTPs to work
- What is DNS and what are A and CNAME records?

### Firewalls

- What is a Firewall and which layers can it operate on?
- How can access be restricted to specific server?
- How can access be restricted to a group of servers in same subnet?
- How can access be restricted to specific applications?

### Tooling for Debugging / Analysis

- `ipcalc`: What does it help with?
- `ping`: What does it help with?
- `traceroute`: What does it help with?
- `netstat`: What does it help with?
- `dig`: What does it help with?

### Which tool to use?

- Which command takes a CIDR and gives back all information about a subnet?
- Which command gives the routers that are involved to access https://example.com
- Which commands gives the IP of https://example.com
- Which command tells if TCP packets can be sent to https://example.com
- Which command gives open ports on local machine?
- Which command gives open network connections?
- Which command resolves the DNS for example.com?
- What is limitations of `ping` and `traceroute` in certain network environments? Can they be blocked to use?

## Web Routing, Load Balancing and Reverse Proxying Fundamentals

### Basic HTTP/S

1. Can you sketch a raw http request and response?
2. What is HTTPS, SSL and TLS?
3. How sketch the steps how do DNS, TLS and HTTP work together when a user browses https://example.com?

### Reverse Proxies and Routing

1. What is reverse proxy?
2. What is a TCP network loadbalancer
3. What is Path and Host based routing?
4. What is SSL/TLS Offloading?
5. What’s the difference between the Http-reverse-proxy and a TCP network loadbalancer and a TCP router?

### Load Balancing

1. Can you describe how DNS based HTTP load balancing works?
2. Can you describe how Reverse-Proxy based HTTP load balancing works?
3. Can you describe how TCP-IP based HTTP load balancing works?

### Failover

1. What is a failover and how does it compare to switchover?
2. Can you describe some load balancing algorithms?
3. What is difference between static and dynamic load balancing algorithm?
4. What is floating ip failover?

### HTTP Status

1. What is a status?
2. What does any status in the range of 200-299 mean?
3. What does any status in the range of 300-399 mean?
4. What does any status in the range of 400-499 mean?
5. What does any status in the range of 500-599 mean?

### Tooling

- `curl`: What does it help with?

### How to use tooling

- Which command shows the status https://example.com responds with?
