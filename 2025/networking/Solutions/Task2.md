# 📡 Task 2: Protocols and Ports for DevOps

DevOps engineers must know which **network protocols** run on which **ports** – this is critical when deploying applications, securing them, or debugging.

---

## 🔐 Common Protocols & Port Numbers

| Protocol | Port | Use Case                         | DevOps Example                      |
|----------|------|----------------------------------|-------------------------------------|
| HTTP     | 80   | Websites (non-secure)            | Default Nginx port                  |
| HTTPS    | 443  | Secure websites (SSL/TLS)        | Hosting secure apps                 |
| FTP      | 21   | File transfer                    | Uploading builds/artifacts          |
| SSH      | 22   | Secure remote login              | Accessing a Linux server            |
| DNS      | 53   | Domain name resolution           | Load balancers, clusters            |
| SMTP     | 25   | Email sending                    | Alerting systems (email)            |
| NTP      | 123  | Time synchronization             | Keeping server clocks aligned       |

---

## 💼 Example Scenarios

- ✅ **SSH to EC2** → `ssh -i key.pem ubuntu@<IP>` → uses port **22**
- ✅ **Browsing HTTPS website** → `https://example.com` → uses port **443**
- ✅ **DNS Resolution** → `dig openai.com` → uses port **53**

---

## 📝 Task Summary

- List out key protocols and their ports
- Share how they help in real-world DevOps tasks
- Optional: Make a diagram or blog with examples
