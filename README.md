# portscanner
Simple Port Scanner (Python)

A beginner-friendly Python Port Scanner that checks common TCP ports on a target host and reports which ports are open. Built using Python's built-in socket module.

📌 Features
Scan common TCP ports
Detect open ports on a target host/IP
Fast and lightweight
Uses Python's built-in socket library
Beginner-friendly cybersecurity project
🛠️ Technologies Used
Python 3
Socket Programming
📂 Project Structure
PortScanner/
│
├── portscanner.py
├── README.md
└── portscanner.png
   
🚀 How It Works

The program:

Accepts a target IP address or domain name.
Attempts to connect to a list of common ports.
Reports ports that are open.
Closes the connection after each scan.

Scanned Ports:

[21, 22, 23, 25, 53, 80, 110, 443]
💻 Installation

Clone the repository:

git clone https://github.com/yourusername/port-scanner.git
cd port-scanner
▶️ Run the Program
python portscanner.py

Example:

Enter IP Address: scanme.nmap.org

Scanning scanme.nmap.org

Port 22 is OPEN
Port 80 is OPEN
📸 Sample Output
Enter IP Address: scanme.nmap.org

Scanning scanme.nmap.org

Port 22 is OPEN
Port 80 is OPEN
🔒 Disclaimer

This project is intended for educational and ethical cybersecurity learning purposes only. Only scan systems that you own or have explicit permission to test.

🎯 Learning Outcomes

Through this project, I learned:

Socket programming in Python
TCP connection establishment
Basic network reconnaissance
Port scanning concepts used in cybersecurity
Host and service discovery fundamentals
🌟 Future Improvements
Multi-threaded scanning
Custom port range support
Service banner grabbing
UDP scanning
Export results to a file
GUI version using Tkinter
👨‍💻 Author

Hemasri Bolishetty
Cybersecurity Student | Python Enthusiast | Aspiring Penetration Tester
