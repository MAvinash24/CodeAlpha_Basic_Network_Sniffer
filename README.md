# CodeAlpha

## Basic_Network_Sniffer

The CodeAlpha Basic Network Sniffer is a simple network packet analyzer built using Python and Scapy. It provides a graphical user interface (GUI) for capturing and analyzing network packets in real-time. Users can start, stop, pause, and resume packet sniffing conveniently through the GUI.

---


### Features
**Real-time Packet Capture**: Captures Ethernet, IP, TCP, UDP, and ICMP packets.
**Packet Analysis**: Displays source and destination MAC/IP addresses, port numbers, protocol information, and payload data.

---

**GUI Controls:**

-Start Sniffing
-Stop Sniffing
-Pause and Resume Sniffing
**Packet Count Display**: Keeps track of the total number of packets captured.
**Scrollable Packet Log**: Displays detailed packet information with timestamps.
**Graceful Exit Handling**: Ensures clean termination when closing the application.

### Prerequisites

Before running the program, make sure you have the following installed:

**Python 3.x**
**Required Python libraries: tkinter, scapy, queue, threading, sys, time**
---
You can install Scapy using:

```
pip install scapy
```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MAvinash24/CodeAlpha_Basic_Network_Sniffer.git
   ```
   
2. Navigate to project directory:
   ```bash
   cd CodeAlpha_Basic_Network_Sniffer
   ```
   
3. Run the code:
   ```bash
   python packet_sniffer.py
   ```

The GUI window will open.

### Screenshot of GUI

![image](https://github.com/user-attachments/assets/b547e8e3-0382-42e8-8836-228c2fe40676)


Click "Start Sniffing" to begin capturing packets.
Use "Pause Sniffing" and "Resume Sniffing" as needed.
Click "Stop Sniffing" to stop the packet capture.
View captured packets in the scrollable display area.


### Notes:

The script may require administrator/root privileges to access network packets.

Linux/macOS: Run using sudo python network_sniffer.py

Windows: Run the script in an administrator command prompt.

Packet capturing will only work if your network interface is in promiscuous mode (if required).

Filtering options can be added to enhance packet capture functionality.


## License:
This project is open-source and provided under the MIT License.
