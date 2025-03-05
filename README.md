

 Intrusion Detection and Prevention System (IDPS)  

 Overview  
This project is a Python-based Intrusion Detection and Prevention System (IDPS) that monitors network traffic, detects suspicious activities, and prevents potential attacks. It utilizes machine learning to classify network traffic and applies real-time alerts and prevention mechanisms to block threats.  

 Features  
- Network Traffic Capture: Monitors and analyzes packets using `scapy` and `pyshark`.  
- Machine Learning-based Detection: Identifies anomalies based on traffic patterns.  
- Real-Time Alerts: Sends email or SMS notifications for suspicious activity.  
- Threat Prevention: Blocks malicious IPs using firewall rules (`iptables`).  
- Logging & Reporting: Maintains a record of detected threats for further analysis.  

 Technologies Used  
- Programming Language: Python  
- Libraries: `scapy`, `pyshark`, `pandas`, `scikit-learn`, `smtplib`, `Flask`  
- Operating System: Linux (Ubuntu recommended)  
- Dataset: NSL-KDD, CICIDS2017  

 Installation  

 Prerequisites  
Ensure you have Python 3.x installed. Install dependencies using:  
```bash
pip install scapy pyshark pandas scikit-learn flask
```

 Run the Project  
```bash
python idps.py


 Usage  
1. Start the IDPS: The system begins monitoring network traffic.  
2. Detect Anomalies: Suspicious activity is flagged based on ML analysis.  
3. Take Action: The system blocks malicious IPs dynamically.  
4. Monitor Logs: View logs and statistics using the Flask dashboard.  

   


