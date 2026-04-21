**User Authentication through Socket Programming**
🛡️A secure, lightweight authentication system that bridges fundamental networking concepts with robust cybersecurity principles. This project integrates Python Socket Programming with the Django Authentication Module to simulate secure access control in corporate and web-based environments.

**👥 Group Members:Omaima Afaq (23K-0044) Hamna Khalid (23K-0700) Afaf Shahid (23K-0678)**

**📖 Project Motivation**
With the constant threat of data breaches, this project addresses the need for secure network-level access control. It provides a practical simulation of secure login systems by establishing encrypted, persistent TCP socket connections between clients and a central server.

**✨ Core FeaturesSecure Socket Communication**: Bidirectional communication using persistent TCP sockets.Django Integration: Utilizes Django’s user model for authentication, session management, and secure password hashing.Encrypted Transmission: All credentials and data are encrypted before being sent over the network to ensure Confidentiality.Data Integrity & Digital Signatures: Implements cryptographic hashing and signatures to prevent data tampering and ensure Non-repudiation.Role-Based Access Control (RBAC): Restricts server functions based on user roles (e.g., Admin vs. User).Dual Interface: Features a CLI for remote client access and a Django Admin Panel for GUI-based management.

**🛠️ Tech Stack**
Programming Language: Python 3.10+ Web Framework: Django 4.x Networking: Python Socket Library Security: Cryptography & Hashlib libraries Development Tools: VS Code 

**🏗️ System Architecture**
The project follows a classic Client-Server model:Client: Initiates a TCP connection and sends encrypted credentials.Server: Receives the request and validates it against the Django authentication backend.Session: Upon successful login, a secure session is established based on the user's assigned role.
