🔍 Nmap Basic to Advanced – Automated Scan Suite

A Bash-based Nmap automation script that performs basic to advanced network reconnaissance in a structured and beginner-friendly way.
Ideal for cybersecurity students, SOC analysts, pentesters, and CTF practice.

📌 Features

This project automates multiple types of Nmap scans in one execution, saving time and ensuring consistent results.

✔ Basic host scan
✔ Ping sweep
✔ Top ports scanning
✔ Full TCP port scan
✔ Service & version detection
✔ OS detection
✔ Default NSE scripts
✔ Vulnerability scanning
✔ HTTP enumeration
✔ SSL/TLS analysis
✔ Aggressive scan
✔ Traceroute discovery

📂 Project Structure
Nmap-Basic-to-Advance/
├── nmap_full_scan.sh
├── nmap_results/
│   ├── basic_<date>.txt
│   ├── ping_<date>.txt
│   ├── top_ports_<date>.txt
│   ├── all_ports_<date>.txt
│   ├── service_version_<date>.txt
│   ├── os_detection_<date>.txt
│   ├── default_scripts_<date>.txt
│   ├── vuln_<date>.txt
│   ├── http_<date>.txt
│   ├── ssl_<date>.txt
│   ├── aggressive_<date>.txt
│   └── traceroute_<date>.txt
└── README.md

▶️ How to Run
1️⃣ Give Execute Permission
chmod +x nmap_full_scan.sh

2️⃣ Run the Script
./nmap_full_scan.sh


📌 Edit the TARGET variable inside the script to scan a different host or IP range.

🛠 Scans Explained

| Scan Type          | Description                         |
| ------------------ | ----------------------------------- |
| Basic Scan         | Checks if the target is reachable   |
| Ping Scan          | Discovers live hosts                |
| Top Ports          | Scans most common ports             |
| Full Port Scan     | Scans all 65,535 TCP ports          |
| Service Version    | Detects running services & versions |
| OS Detection       | Identifies operating system         |
| Default Scripts    | Runs safe NSE scripts               |
| Vulnerability Scan | Checks for known vulnerabilities    |
| HTTP Scan          | Enumerates web services             |
| SSL Scan           | Analyzes SSL/TLS configuration      |
| Aggressive Scan    | OS + version + scripts              |
| Traceroute         | Maps network path to target         |

