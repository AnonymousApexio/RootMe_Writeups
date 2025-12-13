## 🛠️ Essential Tool Categories

### 1. **Reconnaissance & Enumeration**
```yaml
# Network Scanning
nmap                    # Network discovery and security auditing
masscan                 # Fast port scanner
netdiscover             # ARP-based network discovery

# Web Enumeration
gobuster                # Directory/file brute forcing
dirb                    # Web content scanner
ffuf                    # Fast web fuzzer
subfinder               # Subdomain discovery
amass                   # In-depth attack surface mapping
whatweb                 # Web technology identifier
wappalyzer              # Technology stack detection

# Service Enumeration
enum4linux              # SMB enumeration
smbclient               # SMB/CIFS client
ldapsearch              # LDAP enumeration
snmpwalk                # SNMP enumeration
```

### 2. **Web Application Testing**
```yaml
# Proxies
burpsuite               # Web vulnerability scanner & proxy
owasp-zap               # OWASP Zed Attack Proxy

# Specific Vulnerability Scanners
sqlmap                  # Automatic SQL injection
xsstrike                # XSS detection suite
commix                  # Command injection tool
nosqlmap                # NoSQL injection tool

# Manual Testing Tools
curl                    # Command line HTTP client
httpie                  # Modern HTTP client
postman                 # API testing
```

### 3. **Exploitation Frameworks**
```yaml
metasploit-framework    # Penetration testing framework
searchsploit            # Exploit database search
```

### 4. **Password Attacks**
```yaml
hydra                   # Login cracker
medusa                  # Parallel login brute forcer
john                    # John the Ripper password cracker
hashcat                 # Advanced password recovery
crunch                  # Wordlist generator
cewl                    # Custom wordlist generator from websites
```

### 5. **Network & Traffic Analysis**
```yaml
wireshark               # Network protocol analyzer
tcpdump                 # Command line packet analyzer
ettercap                # Man-in-the-middle attacks
responder               # LLMNR/NBT-NS/mDNS poisoner
```

### 6. **Reverse Engineering**
```yaml
ghidra                  # Software reverse engineering suite
radare2                 # Unix-like reverse engineering framework
cutter                  # GUI for radare2
gdb                     # GNU debugger
pwntools                # CTF framework for Python
```

### 7. **Forensics & Steganography**
```yaml
binwalk                 # Firmware analysis tool
foremost                # File recovery tool
steghide                # Steganography tool
exiftool                # Metadata viewer/editor
strings                 # Extract text from binary files
file                    # File type identification
```

### 8. **Wireless & Mobile**
```yaml
aircrack-ng            # WiFi security auditing
apktool                # Reverse engineering Android apps
jadx                   # Dex to Java decompiler
frida                  # Dynamic instrumentation toolkit
```

### 9. **Post-Exploitation**
```yaml
linpeas.sh              # Linux privilege escalation script
winpeas.exe             # Windows privilege escalation
mimikatz                # Windows credential extraction
bloodhound              # Active Directory relationship analyzer
impacket-scripts        # Network protocols Python scripts
```

### 10. **Programming & Scripting**
```yaml
python3                 # General purpose scripting
python3-pip             # Python package manager
gcc                     # C compiler
g++                     # C++ compiler
java                    # Java runtime
nodejs                  # JavaScript runtime
php                     # PHP interpreter
```

### 11. **Container & Cloud**
```yaml
docker                  # Container platform
kubectl                 # Kubernetes command line
aws-cli                 # AWS command line
terraform               # Infrastructure as code
```

### 12. **Miscellaneous Essentials**
```yaml
netcat                  # Networking utility
socat                   # Multipurpose relay
openssl                 # Cryptography toolkit
base64                  # Encoding/decoding
xxd                     # Hex dump utility
vim/nano                # Text editors
```


## 📋 Specialized Tools for Specific Challenge Types

### **For Windows AD Challenges**
```yaml
bloodhound.py           # AD relationship mapper
crackmapexec            # AD penetration testing tool
ldapdomaindump          # AD information dumper
```

### **For Container Challenges**
```yaml
docker                  # Container management
trivy                   # Container vulnerability scanner
dockerscan              # Docker security analysis
```

### **For Crypto Challenges**
```yaml
python3-crypto          # Cryptographic functions
python3-gmpy2           # Mathematics library
rsactftool              # RSA tool for CTFs
```

### **For Mobile Challenges**
```yaml
apktool                 # Android APK analysis
jadx                    # Dex decompiler
frida                   # Dynamic instrumentation
```

## Cybersecurity Kill-chain

![Cybersecurity kill-chain](cybersecurity-killchain.png)