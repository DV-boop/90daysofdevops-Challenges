# Networking Commands Cheat Sheet  

This cheat sheet lists essential networking commands that are useful for DevOps tasks and debugging network-related issues.

---

## **1. Connectivity Testing Commands**

### **ping**  
**Usage:** Check the connectivity to a remote host.  
```bash
ping google.com
```
**Example:**  
```bash
ping 8.8.8.8 -c 4
```  
*Description:* Sends 4 packets to Google’s public DNS to test reachability.

---

## **2. Packet Route Tracing Commands**

### **traceroute (Linux) / tracert (Windows)**  
**Usage:** Shows the route packets take to reach the destination.  
```bash
traceroute google.com
```  
**Windows Version:**  
```cmd
tracert google.com
```  

---

## **3. DNS Lookup Commands**

### **dig (Linux/macOS)**  
**Usage:** Query DNS records for a domain.  
```bash
dig example.com
```  
**To get only the answer:**  
```bash
dig example.com +short
```  

### **nslookup (Windows)**  
**Usage:** Query DNS records for a domain.  
```cmd
nslookup example.com
```

---

## **4. Network Statistics Commands**

### **netstat**  
**Usage:** Display active connections, listening ports, and more.  
```bash
netstat -tuln
```  
*Description:* Lists all listening TCP and UDP ports.

---

## **5. HTTP Request Testing Commands**

### **curl**  
**Usage:** Make HTTP requests to web servers.  
```bash
curl -I https://example.com
```  
*Description:* Fetches HTTP headers from the given URL.

---

## **6. Network Configuration Commands**

### **ifconfig (Linux)**  
**Usage:** View or configure network interfaces (deprecated).  
```bash
ifconfig
```  
**Replacement:**  
```bash
ip a
```

### **ip a (Linux)**  
**Usage:** Show network interfaces and IP addresses.  
```bash
ip a
```

---

## **7. Troubleshooting Commands**

### **tcpdump**  
**Usage:** Capture network packets for analysis.  
```bash
sudo tcpdump -i eth0
```  

### **netcat (nc)**  
**Usage:** Check open ports, send data, or listen for connections.  
```bash
nc -zv example.com 80
```  

---

This cheat sheet is intended to help DevOps professionals troubleshoot and manage networks efficiently.
```  
