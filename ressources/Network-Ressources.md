## 🌐 Essential Network Analysis Tools

### **Primary Packet Analyzers**
- **Wireshark** - Main GUI packet analyzer
- **TShark** - Command-line version of Wireshark
- **tcpdump** - Classic command-line packet analyzer

### **Specialized Protocol Tools**

#### **FTP/TELNET/POP/SSL**
```bash
ftp
lftp
ncftp
FileZilla (GUI)

telnet
netcat (nc)
putty (for Windows)

openssl s_client
sslstrip, sslsplit
```

#### **DNS Tools**
```bash
dig
nslookup
host
dnsrecon
dnsenum
fierce
```

#### **LDAP Tools**
```bash
ldapsearch
ldapdomaindump
windapsearch
Apache Directory Studio
JXplorer
```

#### **SNMP Tools**
```bash
snmpwalk
snmpget
onesixtyone
snmp-check
```

#### **SIP/VoIP**
```bash
sipgrep
sipsak
svcrack (SIP password cracker)
```

#### **Wireless/RF Tools**
```bash
bluetoothctl
hcitool
ubertooth
bluelog

gnuradio
gqrx
rtl-sdr (software defined radio)
audacity (for audio analysis)

aircrack-ng suite
kismet
wireshark (with WiFi capture)
```

## 🛠️ Specialized Challenge Tools

### **Kerberos/NTLM Authentication**
```bash
kinit
klist
GetUserSPNs
GetNPUsers

responder
ntlmrecon
hashcat
```

### **CISCO Password Recovery**
```bash
cisco-decrypt (various implementations)
john the ripper (with cisco rules)
```

### **GSM (Global System for Mobile)**
```bash
airprobe
wireshark with GSM plugin
kalibrate-rtl
```

### **WEP/WPA/WPA2/WPA3**
```bash
aircrack-ng suite (airmon-ng, airodump-ng, aireplay-ng)
hashcat
hcxpcapngtool
```

### **ARP Spoofing/MitM**
```bash
# ARP spoofing
arpspoof, ettercap
driftnet (image capture)
dsniff (password sniffing)

# MitM frameworks
ettercap (GUI and CLI)
bettercap
```

## 🔧 Programming/Scripting Tools

### **Python with Essential Libraries**
```bash
- scapy (packet manipulation)
- impacket (network protocols)
- pwntools (CTF framework)
- cryptography
- pyshark
- numpy, scipy (signal processing)
```

## 📚 Learning Resources
### **Protocol Documentation**
- [RFC documents](https://www.rfc-editor.org/rfc-index.html)
- [Wireshark documentation and sample captures](https://www.wireshark.org/docs/)
- [Protocol Handbook](https://bkarak.wizhut.com/www/lectures/networks-07/NetworkProtocolsHandbook.pdf)