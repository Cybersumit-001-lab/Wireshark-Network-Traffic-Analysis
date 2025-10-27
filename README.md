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
| **DNS** | `dns` | Used for domain name lookups |
| **TCP** | `tcp` | Reliable data transport between hosts |
| **HTTP** | `http` | Web traffic communication |

---

## 📊 Summary
- Found multiple protocols: **DNS**, **TCP**, **HTTP**
- Observed packet flow between local machine and external servers.
- Wireshark helped visualize how data travels across the network.

---

