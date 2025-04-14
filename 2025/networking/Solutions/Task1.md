# 🌐 Task 1: Understanding OSI & TCP/IP Models

Networking is the backbone of DevOps. This task introduces you to the **OSI** and **TCP/IP** models – the two key models that explain how data moves from one device to another.

---

## 🧱 OSI Model (7 Layers)

OSI (Open Systems Interconnection) is a **conceptual model** that explains how data travels across networks in **7 layers**.

### 📊 OSI Layers & Real-World Examples

| Layer | Name              | Purpose                                      | Real-Life Example                            |
|-------|-------------------|----------------------------------------------|-----------------------------------------------|
| 7     | Application       | Interfaces for user apps                     | Web browser using HTTP                        |
| 6     | Presentation      | Formats, compresses, encrypts data           | YouTube video compression (MP4)               |
| 5     | Session           | Starts/stops communication                   | Staying logged into online banking            |
| 4     | Transport         | Ensures reliable delivery (TCP/UDP)          | Watching Netflix (TCP or UDP used)            |
| 3     | Network           | Handles routing, logical addressing (IP)     | Data finds the route to `google.com`          |
| 2     | Data Link         | Ensures point-to-point delivery (MAC)        | Wi-Fi uses MAC addresses to send data         |
| 1     | Physical          | Sends raw bits over hardware                 | Ethernet cable or Wi-Fi radio waves           |

📌 **Mnemonic**: *All People Seem To Need Data Processing*

---

## 💡 TCP/IP Model (4 Layers)

TCP/IP is a **real-world model** used by the Internet. It simplifies OSI into **4 layers**.

### 🌍 TCP/IP Layers and Uses

| Layer            | Role                                   | Example Services            |
|------------------|----------------------------------------|-----------------------------|
| Application       | User-facing protocols                  | HTTP, HTTPS, SSH, DNS       |
| Transport         | Ensures data arrives reliably          | TCP, UDP                    |
| Internet          | Moves data between networks            | IP, ICMP                    |
| Network Access    | Sends bits over hardware               | Ethernet, Wi-Fi             |

✅ It's the model behind the **entire Internet**!

---

## 📝 Task Summary

✔️ Study the layers of both models  
✔️ Write real-world examples like above  
✔️ Add this to your blog or GitHub notes  
