# 🔍 Automated Nmap Port Scanner

<p align="center">
  <b>Fast • Efficient • Reconnaissance Ready</b><br>
  A Bash-based automated port scanner using Nmap for full-range scanning, service detection, and structured logging.
</p>

---

## 🚀 Features

* 🔎 **Full Port Scan** — Scans all 65,535 ports (`-p-`)
* ⚡ **Optimized Performance** — Faster scanning using `-T4`
* 🧠 **Service Detection** — Identifies running services & versions (`-sV`)
* 📁 **Automated Logging** — Saves results in timestamped output files
* 🛠️ **Lightweight & Simple** — Built using Bash + Nmap

---

## 🧰 Tech Stack

* **Bash Scripting**
* **Nmap**
* **Linux (Kali Linux recommended)**

---

## 📂 Project Structure

```
nmap-port-scanner/
│── scanner.sh
│── README.md
│── .gitignore
│── sample_output.txt
```

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/nmap-port-scanner.git

# Navigate into the project
cd nmap-port-scanner

# Make script executable
chmod +x scanner.sh
```

---

## ▶️ Usage

```bash
./scanner.sh <target>
```

### 📌 Example

```bash
./scanner.sh 192.168.1.1
```

---

## 📊 Sample Output

```
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 8.2
80/tcp   open  http    Apache httpd 2.4.41
443/tcp  open  https   Apache httpd
```

---

## 💡 How It Works

* Executes a full-range Nmap scan (`-p-`)
* Applies faster timing template (`-T4`)
* Detects service versions (`-sV`)
* Redirects output into a timestamped file for analysis

---

## 🎯 Use Cases

* 🔐 Network Reconnaissance
* 🛡️ Vulnerability Assessment
* 🧪 Penetration Testing Labs
* 📚 Cybersecurity Learning

---

## ⚠️ Disclaimer

> This tool is intended for **educational purposes and authorized testing only**.
> Do not use it on systems without permission.

---

## 🔥 Future Enhancements

* [ ] Service-based filtering (only open ports)
* [ ] JSON/CSV structured output
* [ ] Multi-target scanning
* [ ] Integration with vulnerability scanners
* [ ] Web dashboard for visualization

---

## 👨‍💻 Author

**Sharookh**
Cybersecurity Enthusiast | Ethical Hacker | Developer

---

## ⭐ Support

If you like this project:

* ⭐ Star the repo
* 🍴 Fork it
* 🛠️ Contribute

---

<p align="center">
  🚀 Built with passion for cybersecurity
</p>
