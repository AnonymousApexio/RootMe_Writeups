## 🛠️ Essential Forensic Tools

### **Memory Analysis**
```yaml
  - volatility3
  - rekall
  - bulk_extractor
```

### **Network Analysis**
```yaml
  - wireshark
  - tcpdump
  - tshark
  - netsniff-ng
  - ntopng
  - bro/zeek
```

### **Disk & File Analysis**
```yaml
  - sleuthkit
  - autopsy
  - foremost
  - scalpel
  - testdisk
  - photorec
  - binwalk
  - bulk_extractor
```

### **Log Analysis**
```yaml
  - logwatch
  - lnav
  - goaccess
  - jq (for JSON logs)
```

### **Windows Forensics**
```yaml
  - regripper
  - python3-pip
    - python-registry
    - libscca-python
    - pypykatz
```

## 📋 Challenge-Specific Tools

### **Memory Forensics Challenges**
- **Volatility 2/3** - Primary memory analysis
- **Rekall** - Alternative memory analysis
- **Bulk Extractor** - Bulk data extraction
- **Strings** - Built-in string extraction

### **Network Capture Analysis**
- **Wireshark** - GUI packet analysis
- **Tshark** - CLI packet analysis
- **Tcpdump** - Packet capture
- **NetworkMiner** - Network forensic analysis
- **CapAnalysis** - Web-based pcap analysis

### **Windows AD & LDAP Challenges**
```yaml
  - impacket-scripts
  - bloodhound
  - bloodhound-python
  - crackmapexec
  - ldapsearch
```

### **Docker & Container Forensics**
```yaml
  - docker.io
  - dive (docker image analysis)
  - trivy (vulnerability scanner)

  # Python packages
  - docker
  - docker-squash
```

### **Mobile Forensics (Android/iOS)**
```yaml
  - adb (Android Debug Bridge)
  - sqlitebrowser
  - jadx (Dex to Java decompiler)
  - MobSF (Mobile Security Framework)
  - Objection (Mobile runtime exploration)
  - Frida (Dynamic instrumentation)
```

### **Steganography & File Carving**
```yaml
  - steghide
  - exiftool
  - strings
  - hexedit
  - xxd
  - binwalk
  - foremost
  - scalpel
```

### **Cryptography & Hashing**
See [Cryptanalysis-Ressources.md](Cryptanalysis-Ressources.md)

## 🎯 Specific Challenge Tools

### **Command & Control Series**
```yaml
- YARA (malware pattern matching)
- Suricata (IDS)
- Snort (IDS)
- Cuckoo Sandbox (malware analysis)
- Any.Run (malware analysis)
```

### **Web Log Analysis**
```yaml
  - goaccess
  - awstats
  - logcheck
  - jq (JSON processing)
```

### **Ransomware & Malware Analysis**
```yaml
  - radare2
  - ghidra
  - cutter
  - strings
  - file
  
  Python:
  - pefile
  - yara-python
```

### **macOS & iOS Forensics**
```yaml
- Plist Editor (property list files)
- SQLite Browser (database analysis)
- iOS Backup Analyzer tools
```

## 🐍 Python Libraries for Forensics
```yaml
  - pytsk3 (The Sleuth Kit bindings)
  - dfvfs (Digital Forensics Virtual File System)
  - libscca-python (Windows Prefetch)
  - pypykatz (Mimikatz functionality)
  - impacket
  - python-registry
  - pillow (image analysis)
  - scapy (packet manipulation)
  - pandas (data analysis)
  - jupyter (notebooks for analysis)
```

### **Browser Extensions**
- **Wappalyzer** - Technology identification
- **User-Agent Switcher** - HTTP header manipulation