# Computer Networks Project 1

## 📌 Project Description  
This repository contains the implementation and report for **Computer Networks (ENCS3320) Project 1**.  
The project explores fundamental networking tools, socket programming, and web server implementation.  

### 🔹 Part 1: Networking Tools & DNS Capture  
- **Ping** – measuring round-trip time (RTT) and connectivity.  
- **Tracert** – tracing the route of packets and analyzing latency at each hop.  
- **Nslookup** – resolving domain names to IP addresses (and reverse lookup).  
- **Telnet** – establishing remote connections to servers.  
- **Wireshark** – capturing DNS messages to analyze network communication.  

### 🔹 Part 2: UDP Client-Server & Peer Communication  
- Implemented a **UDP server** listening on port `5051`.  
- Multiple peers can send and receive messages.  
- Each peer displays received messages along with the sender’s name and timestamp.  
- A peer can request to display specific messages (e.g., typing `2D` shows the second received message).  
- Implemented in **Python** using `socket` programming.  

### 🔹 Part 3: Simple Web Server  
- Implemented a **web server** (port `6060`) using **Python sockets**.  
- Supports serving multiple file types with correct Content-Type headers:  
  - `.html` → `text/html`  
  - `.css` → `text/css`  
  - `.png` → `image/png`  
  - `.jpg` → `image/jpeg`  
- Handles form inputs (`myformEN.html`, `myformAR.html`).  
- Supports **redirects (307 Temporary Redirect)** for custom paths.  
- Returns a **custom 404 error page** when a resource is not found.  

---

## 🛠️ Tools & Technologies  
- **Python** (socket programming)  
- **Wireshark** (packet capture & DNS analysis)  
- **Command line tools** (`ping`, `tracert`, `nslookup`, `telnet`)  
- **HTML & CSS** (for testing the web server)  

---

