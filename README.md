# Port Scanner Tool 🔎

A simple Python-based port scanner to check open ports on one or more targets.

## Features ✨
- Scans a single target or multiple targets.
- Allows you to specify the number of ports to scan.
- Displays open ports in a clean format.

## How It Works ⚛️
This tool uses Python's `socket` module to connect to specified ports on the given target(s). If a connection is successful, the port is marked as open.

## Requirements ⭐
- Python 3.x
- Basic understanding of networking

## Usage 🚀
1. Clone this repository:
   ```bash
   git clone https://github.com/fadlyfatih1/simple-portscanner.git
   cd simple-portscanner
   ```

2. Run the script:
   ```bash
   python3 portscanner.py
   ```

Example input/output:
```text
[*] Enter Targets To Scan (split them by ,): 192.168.1.1
[*] Enter How Many Ports You Want To Scan: 1000

 Starting Scan For 192.168.1.1
[+] Port Opened 22
[+] Port Opened 80
[+] Port Opened 443
```

## Notes 📊
- Make sure to run this script with proper authorization. Scanning unauthorized networks is illegal and unethical.
- The script is basic and does not include advanced features like multi-threading or service detection.
