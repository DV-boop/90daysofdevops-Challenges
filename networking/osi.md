# OSI & TCP/IP Models

## OSI Model

The **OSI (Open Systems Interconnection) Model** is a conceptual framework used to understand network interactions in seven layers. Here’s how each layer applies to real-world scenarios:

### 1. Application Layer (Layer 7)
- **Function:** This is the topmost layer where end-user applications interact.
- **Example:** 
  - **HTTP** for web browsing
  - **SMTP** for sending emails

### 2. Presentation Layer (Layer 6)
- **Function:** It formats or translates data between the application and transport layers.
- **Example:**
  - **Data encryption** and compression (like **TLS/SSL** for secure communication)

### 3. Session Layer (Layer 5)
- **Function:** Manages sessions or connections between computers.
- **Example:** 
  - **NetBIOS** manages sessions in file sharing.

### 4. Transport Layer (Layer 4)
- **Function:** Responsible for end-to-end communication and error correction.
- **Example:** 
  - **TCP (Transmission Control Protocol)** for reliable communication
  - **UDP (User Datagram Protocol)** for faster communication but without guaranteed delivery.

### 5. Network Layer (Layer 3)
- **Function:** Handles routing and forwarding of data packets.
- **Example:**
  - **IP (Internet Protocol)** ensures data packets are delivered to the correct destination.

### 6. Data Link Layer (Layer 2)
- **Function:** Provides node-to-node data transfer and error correction.
- **Example:** 
  - **Ethernet frames** used for local network communication.

### 7. Physical Layer (Layer 1)
- **Function:** Deals with the physical connection between devices, including cables, switches, and radio signals.
- **Example:** 
  - **Ethernet cables**, **Wi-Fi signals**

---
## OSI Model

The **OSI (Open Systems Interconnection) Model** is a conceptual framework used to understand network interactions in seven layers. Here’s a table that explains each layer and its real-world application:

| **Layer**               | **Function**                                                    | **Example**                                                                 |
|-------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------------------|
| **Application Layer (Layer 7)**  | End-user application interaction                                | **HTTP** for web browsing, **SMTP** for sending emails                      |
| **Presentation Layer (Layer 6)** | Formats or translates data between the application and transport layers | **TLS/SSL** for secure communication, data encryption                       |
| **Session Layer (Layer 5)**       | Manages sessions or connections between computers                 | **NetBIOS** for file sharing sessions                                      |
| **Transport Layer (Layer 4)**     | End-to-end communication and error correction                   | **TCP** for reliable communication, **UDP** for faster, less reliable communication |
| **Network Layer (Layer 3)**       | Handles routing and forwarding of data packets                   | **IP (Internet Protocol)** for packet delivery                              |
| **Data Link Layer (Layer 2)**     | Node-to-node data transfer and error correction                | **Ethernet frames** for local network communication                         |
| **Physical Layer (Layer 1)**      | Physical connection between devices (cables, switches, etc.)     | **Ethernet cables**, **Wi-Fi signals**                                       |

-----------------------------------------------------------------------------------------------------------------------------------
## TCP/IP Model

The **TCP/IP (Transmission Control Protocol/Internet Protocol)** model is the basis of the internet and networking. It's more streamlined with 4 layers:

### 1. Application Layer
- **Function:** This combines the OSI’s Application, Presentation, and Session layers.
- **Example:** 
  - **HTTP, FTP, DNS**

### 2. Transport Layer
- **Function:** Responsible for data transfer between devices.
- **Example:**
  - **TCP** (for reliable transmission)
  - **UDP** (for faster transmission)

### 3. Internet Layer
- **Function:** Manages the addressing and routing of data.
- **Example:**
  - **IP (Internet Protocol)**
  - **ICMP (Internet Control Message Protocol)** for sending error messages.

### 4. Network Access Layer
- **Function:** Combines the OSI’s Data Link and Physical layers.
- **Example:**
  - **Ethernet** (for LAN)
  - **Wi-Fi** (for wireless networks)

---
## TCP/IP Model

The **TCP/IP (Transmission Control Protocol/Internet Protocol)** model is the basis of the internet and networking. Here's a table to compare the layers and their examples:

| **Layer**               | **Function**                                                    | **Example**                                                                 |
|-------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------------------|
| **Application Layer**    | Combines the OSI’s Application, Presentation, and Session layers | **HTTP**, **FTP**, **DNS**                                                   |
| **Transport Layer**      | Responsible for data transfer between devices                   | **TCP** (reliable transmission), **UDP** (faster transmission)            |
| **Internet Layer**       | Manages addressing and routing of data                          | **IP (Internet Protocol)**, **ICMP** (error messages)                      |
| **Network Access Layer** | Combines the OSI’s Data Link and Physical layers                | **Ethernet**, **Wi-Fi**                                                      |
