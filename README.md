# 90daysofdevops-challenges
"My DevOps Networking Challenge for 90 Days of DevOps."
# DevOps Challenge: Week 1 — Networking Challenge

Welcome to **Week 1 of the 90 Days of DevOps - 2025 Edition!** This week focuses on mastering networking concepts, protocols, and practical hands-on tasks. Below are the deliverables and guides for this week’s challenge.

---

## Directory Structure
```
DevOps-Challenge/
├── README.md
├── cheatsheets/
│   └── Networking-Commands.md
└── guides/
    └── AWS-Security-Groups.md
```

### [README.md](./README.md)
This file provides an overview of the DevOps Challenge for Week 1, task descriptions, and submission instructions.

### [cheatsheets/Networking-Commands.md](./cheatsheets/Networking-Commands.md)
Contains a cheat sheet for essential networking commands and their practical uses.

### [guides/AWS-Security-Groups.md](./guides/AWS-Security-Groups.md)
Provides a step-by-step guide to setting up and configuring AWS EC2 Security Groups for secure cloud instances.

---

## **Networking Challenge Tasks**

### **Task 1: OSI & TCP/IP Models**
- Learn about OSI and TCP/IP models.
- Write examples of how each layer applies to real-world scenarios.

### **Task 2: Protocols and Ports for DevOps**
- Study commonly used protocols and their port numbers.
- Write documentation on the relevance of each protocol.

### **Task 3: AWS EC2 and Security Groups**
- Launch an AWS EC2 instance.
- Configure Security Groups and document the steps.

### **Task 4: Hands-On with Networking Commands**
- Practice essential networking commands.
- Create a cheat sheet summarizing each command.

---

# Cheatsheet: Networking Commands

## Networking Commands and Usage

### **1. ping**
**Command:**
```bash
ping <domain-name>
```
**Purpose:** Checks the connectivity to a specific domain or IP address.
**Example:**
```bash
ping google.com
```

### **2. traceroute / tracert**
**Command:**
```bash
traceroute <domain-name>  # Linux
tracert <domain-name>     # Windows
```
**Purpose:** Traces the packet path between your system and the target host.
**Example:**
```bash
traceroute google.com
```

### **3. netstat**
**Command:**
```bash
netstat -an
```
**Purpose:** Displays network connections and statistics.

### **4. curl**
**Command:**
```bash
curl <URL>
```
**Purpose:** Makes HTTP requests and fetches response data.
**Example:**
```bash
curl http://example.com
```

### **5. dig / nslookup**
**Command:**
```bash
dig <domain-name>       # Linux
dslookup <domain-name>   # Windows
```
**Purpose:** Performs DNS lookups to retrieve domain information.
**Example:**
```bash
dig google.com
```

---

# AWS Security Groups Guide

## **How to Launch an AWS EC2 Instance and Configure Security Groups**

### **Step 1: Go to AWS Console**
1. Log in to your AWS Management Console.
2. Navigate to the **EC2 Dashboard**.

### **Step 2: Launch an EC2 Instance**
1. Click “Launch Instance.”
2. Choose the **Amazon Linux 2 AMI**.
3. Select the instance type as **t2.micro (Free Tier eligible)**.
4. Click **Next** to configure instance details.

### **Step 3: Configure Security Groups**
1. Set up the Security Group rules as follows:
   - **SSH (port 22):** Allow from your IP.
   - **HTTP (port 80):** Allow from anywhere.
2. Name your Security Group and save it.

### **Step 4: Launch and Connect**
1. Click “Launch.”
2. Select an existing key pair or create a new one.
3. Connect to the instance using SSH:
   ```bash
   ssh -i <key-pair-name.pem> ec2-user@<public-ip>
   ```

### **Step 5: Verify Configuration**
1. Use commands like `ping`, `curl`, and `traceroute` to test network access.
2. Ensure the Security Group rules are working correctly.

---

This structure and documentation should guide you in successfully completing Week 1 and keeping your repository organized and informative. Happy Networking! 🚀

