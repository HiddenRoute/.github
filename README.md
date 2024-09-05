# HiddenRoute TODO:

**Nodes:**
___________________________________
*1) Implement all authentication methods(User/Password, GSSAPI(Kerberos))*

*2) Implement IPv6, Domain Name*

*3) Implement HTTP requests(GET, HEAD, POST, PUT, DELETE, CONNECT, OPTIONS, TRACE, PATCH)*

*4) Implement connection with Tor Directory Server*

*5) Implement Tor Protocol[Circ. ID, Circ. CMD, DATA]*

**Kerberos:**
___________________________________
*1) Implement KDC (Key Distribution Center)*

**In KDC:**
___________________________________
*1) Implement AS (Authentication Server)*

*2) Implement TGS (Ticket Granting Server)*

**Monitoring Server:**
___________________________________
*1) Implement Health Check*

*2) Implement nodes Load Balancer for Tor Directory Server* 

*3) Implement client with GUI*

**Tor Directory Server:**
___________________________________
*1) Implement consensus document("https://support.torproject.org/glossary/consensus")*

*2) Implement client handler*

**Client:**
___________________________________
*1) Implement Raw(IPv4, IPv6), HTTP(Domain Name) connection(Console GUI for Raw connection, and mini browser for HTTP connection)*

### Update the client during development for testing purposes
### Nodes(1-3, without GSSAPI) --> Kerberos(All) --> In KDC(All) --> Nodes(1 -- GSSAPI) --> Monioring Server(All) --> Tor Directory Server(All) --> Nodes(4-5) --> Implement TLS/SSL(Nodes,KDC,Tor Directory, Monitoring Server)
