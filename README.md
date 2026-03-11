🖥️ Automated Platform Surveillance System

📝 Overview  
A Python-based system monitoring and logging tool that periodically collects system information and stores it in timestamped log files.  
The application tracks CPU usage, memory usage, disk utilization, network statistics, and running processes to provide continuous system monitoring.

🚀 Features
Periodic system monitoring at fixed intervals  
Automatic creation of timestamped log files  
Tracks CPU usage and RAM usage   
Records network sent and received statistics  
Captures process information (PID, name, user, status)  
Logs CPU and memory usage per process  

🛠️ Tech Stack
Python  
psutil library  
OS module  
Console (CLI)

▶ How to Run
Install required dependency

pip install psutil

Run the monitoring script

python monitor.py

Stop execution anytime using

Ctrl + C
