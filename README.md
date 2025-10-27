# 🧠 Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
Capture live network packets using Wireshark and identify different protocols and traffic types.

---

## 🧰 Tools Used
- **Wireshark** (free and open-source)
- **Operating System:** Kali Linux 

---

## 🪜 Steps Performed
1. Installed Wireshark.
2. Started capture on the active network interface (Wi-Fi).
3. Browsed websites and pinged `google.com` to generate traffic.
4. Stopped capture after 1 minute.
5. Filtered by protocols — DNS, TCP, HTTP.
6. Exported the capture file as `.pcap`.
7. Wrote a short report summarizing findings.

---

## 🔍 Protocol Filters Used
| Protocol | Filter Command | Description |
|-----------|----------------|--------------|
| **ARP** | `arp` | Resolves MAC addresses in local networks |
| **ICMP** | `icmp` | Used for ping and diagnostic communication |
| **DNS** | `dns` | Resolves domain names to IP addresses |
| **TCP** | `tcp` | Provides reliable data transport between hosts |


---

## 📊 Summary
- Found multiple protocols: **DNS**, **TCP**, **HTTP**
- Observed packet flow between local machine and external servers.
- Wireshark helped visualize how data travels across the network.

---

## 📁 Repository Contents
capture/ → contains the .pcap capture file
report/ → detailed analysis report
filters/ → protocol filter commands
README.md → main documentation


---

## 🧩 Conclusion
This task demonstrated how Wireshark captures and analyzes real network traffic.  
By using filters, I was able to identify and understand key network protocols.

