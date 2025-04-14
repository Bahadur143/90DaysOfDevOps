# ☁️ Task 3: AWS EC2 and Security Groups

Learn to launch a virtual server in the cloud and **secure it** using Security Groups.

---

## 🔧 What Is an EC2 Instance?

An **EC2 instance** is a virtual machine on AWS. You can:
- Host websites
- Run Docker containers
- Test applications

---

## 🔐 What Are Security Groups?

Security Groups are like **firewalls** that allow or block traffic to your instance based on:
- **Port Number**
- **Protocol**
- **Source IP**

---

## 🛠️ Step-by-Step: Launch EC2 & Set Security Rules

1. Go to [AWS Console](https://aws.amazon.com)
2. Launch a free-tier **Ubuntu EC2 instance**
3. In the **Security Group** section:
   - Allow port `22` (SSH) – to connect via terminal
   - Allow port `80` (HTTP) – to serve websites
   - Allow port `443` (HTTPS) – for secure traffic

### ✅ Example Security Group Table

| Type   | Protocol | Port | Source        | Purpose                |
|--------|----------|------|---------------|------------------------|
| SSH    | TCP      | 22   | My IP         | Connect via terminal   |
| HTTP   | TCP      | 80   | Anywhere      | Public web traffic     |
| HTTPS  | TCP      | 443  | Anywhere      | Secure web traffic     |

---

📝 **Task:** Write a blog or README documenting how you launched the EC2 instance and secured it.

