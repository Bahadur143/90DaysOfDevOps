# 🛠️ Task 4: Networking Commands Cheat Sheet

These commands help DevOps professionals **troubleshoot**, **monitor**, and **test** network issues.

---

## 📘 Essential Networking Commands

| Command     | Purpose                                      | Example                        |
|-------------|----------------------------------------------|--------------------------------|
| `ping`      | Check if a server is reachable               | `ping google.com`              |
| `traceroute`| Shows the path packets take to a server      | `traceroute github.com`        |
| `netstat`   | Shows network connections and ports          | `netstat -tuln`                |
| `curl`      | Sends HTTP requests to a server              | `curl https://example.com`     |
| `dig`       | Checks DNS info for a domain                 | `dig google.com`               |
| `nslookup`  | DNS lookup tool                              | `nslookup openai.com`          |

---

## 🚀 Real Use Cases

- `curl` → Test API endpoints in CI/CD pipelines
- `ping` → Check server or DNS connectivity
- `netstat` → Verify if ports are open for Nginx/Docker
- `dig` / `nslookup` → Debug DNS issues in Kubernetes

---

📝 **Task:** Create a mini guide or post with screenshots of your command outputs + explain when you'd use each in DevOps.

