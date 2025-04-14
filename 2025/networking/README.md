# 🌐 Task 1: Understanding OSI & TCP/IP Models

Understanding how data flows in a network is the foundation of DevOps and system administration.

---

## 📦 OSI Model - 7 Layers (Theoretical Model)

Each layer in OSI has a job — think of it like mailing a letter:

| Layer | Name              | Function                                             | Real-World Example                          |
|-------|-------------------|------------------------------------------------------|----------------------------------------------|
| 7     | Application       | User interface, network services                     | Browsing with Chrome (uses HTTP)             |
| 6     | Presentation      | Data formatting, encryption, compression             | Video compression, SSL/TLS encryption        |
| 5     | Session           | Manages sessions between systems                     | Online banking login session                 |
| 4     | Transport         | Reliable delivery, error checking                    | Watching Netflix (uses TCP or UDP)           |
| 3     | Network           | Routing data between networks                        | IP addresses determine destination server     |
| 2     | Data Link         | Physical addressing (MAC), error detection           | Your Wi-Fi router sends packets to your laptop |
| 1     | Physical          | Physical connection (cables, signals)                | Ethernet cable, Wi-Fi signal                 |

🧠 **Tip**: Remember OSI with — *"All People Seem To Need Data Processing"*

---

## 🚀 TCP/IP Model - 4 Layers (Real-World Internet Model)

| Layer             | Purpose                                 | Examples                      |
|------------------|------------------------------------------|-------------------------------|
| Application       | End-user applications & services         | HTTP, DNS, SSH                |
| Transport         | Reliable/unreliable delivery             | TCP, UDP                      |
| Internet          | Logical addressing and routing           | IP, ICMP                      |
| Network Access    | Physical transmission and MAC addressing | Ethernet, Wi-Fi               |

✅ TCP/IP is the model **used in the internet today**.

---

## ✅ Summary

- **OSI** = Learning/Reference model (7 layers)
- **TCP/IP** = Internet/Practical model (4 layers)
- Helps DevOps engineers debug, monitor, and build infrastructure

📝 **Task:** Add real-life examples of each layer to show your understanding (like above).
