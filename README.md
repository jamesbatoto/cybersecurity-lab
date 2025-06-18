# 🛡️ Cybersecurity Home Lab (MyDFIR-Inspired)

This project showcases a hands-on cybersecurity lab inspired by the MyDFIR YouTube series. The lab simulates a networked environment for threat detection, system hardening, and log analysis using open-source tools.

## 🏗️ Lab Architecture

- **Kali Linux** (Attacker Box)
- **Windows 10 VM** (Target with Splunk + Sysmon)
- **Internal Network** via VirtualBox
- Optional NAT adapter for internet access (updates & tooling)

## 🔧 Tools & Configuration

| Tool             | Purpose                            |
|------------------|-------------------------------------|
| Kali Linux       | Enumeration and reconnaissance      |
| Nmap             | Port scanning and service detection |
| Sysmon           | System monitoring and event logging |
| Splunk           | Ingestion and visualization         |
| VirtualBox       | VM segmentation and isolation       |

## 🧠 Key Capabilities Demonstrated

- Static IP & gateway configuration via `nmcli`
- Network traffic isolation and adapter setup
- Port and OS fingerprinting using Nmap (`-sV`, `-Pn`, `-f`, `-oA`)
- Splunk dashboard integration with Sysmon logs
- Secure dual-NIC VM design (Internal + NAT)


## 📘 Lessons Learned

- Troubleshooting filtered ports & unreachable hosts
- Real-world applicability of internal threat detection
- Importance of log centralization and baseline snapshots

## 🔗 Reference

- [MyDFIR Home Lab Series on YouTube](https://www.youtube.com/playlist?list=PLG6KGSNK4PuBWmX9NykU0wnWamjxdKhDJ)
- [Sysmon Config GitHub Repo](https://github.com/SwiftOnSecurity/sysmon-config)

---

