## Hi there 👋

🌐 Our team is working on creating an innovative network similar to Tor, but with significant improvements. We are building it from scratch in C++ 🚀 to achieve high performance and optimization that we've long desired. Our goal is not just to replicate existing solutions but to create something powerful, secure, and reliable.

🔧 Our system is based on microservice architecture 🧩, which provides flexibility and resilience. The core components include:

    🖧 Nodes — the foundation of the network through which all traffic flows.
    🗂️ Directory Servers (Tor Directory) — distributed servers that store necessary information about nodes for routing.
    🔑 KDC (Key Distribution Center) — for key management and authentication.
    🖥️ Monitoring Servers — ensuring the health of all nodes and the overall stability of the system.

💻 We are also developing a desktop client in Dart (Flutter) to provide a user-friendly interface for our network. The client will allow communication with servers in two ways:

    📜 Through the console for Raw connections (IPv4, IPv6),
    🌐 Through a mini-browser for HTTP/S connections (Domain Name).

🔗 Communication between the network nodes will be conducted through a custom protocol, which is a combination of SOCKS5 and the Tor Protocol (supporting fields Circ. ID, CMD, DATA). For enhanced security, we are implementing multi-level authentication:

    🛡️ GSSAPI for comprehensive and secure authentication,
    🔑 User/Password for convenience,
    🚪 No Auth for nodes communicating directly with each other.

🔒 Cryptography is at the heart of our project's security framework. We employ a sophisticated suite of cryptographic algorithms to safeguard communication and ensure data integrity:

    RSA is utilized for secure key exchange and authentication, leveraging its asymmetric encryption to establish a robust and confidential connection between parties.
    Diffie-Hellman (DH) facilitates key agreement, enabling two parties to securely establish a shared secret over an insecure channel, enhancing the security of their communications.
    RC4 is used for stream encryption, providing efficient and flexible encryption for data in transit, ensuring that information remains protected and confidential as it travels across the network.

Together, these encryption methods create a strong defense against unauthorized access and guarantee the reliability and privacy of data transmission within our network. 🔐

All of these technologies and components are being developed with one goal in mind — to create a fast, secure, and efficient network for anonymous communication and data transfer. 🌍 We believe that with our architecture and protocols, the future of decentralized networks will become more accessible and reliable!
