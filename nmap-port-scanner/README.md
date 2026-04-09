# 🔍 Automated Nmap Port Scanner

## 📌 Description
This project is a Bash-based automated port scanner that uses Nmap to perform full-range port scanning and service/version detection. The results are saved into a file for further analysis.

## 🚀 Features
- Scans all 65,535 ports (`-p-`)
- Detects services and versions (`-sV`)
- Optimized scanning speed (`-T4`)
- Automatically saves output to a timestamped file

## 🛠️ Technologies Used
- Bash
- Nmap
- Linux

## ⚙️ Usage

```bash
chmod +x scanner.sh
./scanner.sh <target>