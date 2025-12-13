## 🛠️ Essential Cryptanalysis Tools

### **Encoding/Decoding Tools**
```yaml
# ASCII/Text conversion
xxd, hexdump, od

# UU encoding
uudecode
```

### **Hash Cracking**
```yaml
john
hashcat
hashid # Identify hashes formats
```
**Specific formats:**
- **LM/NT/DCC/DCC2:** John, Hashcat
- **MD5/SHA-2/SHA-3:** Hashcat, online crackers

### **Classical Ciphers**
```yaml
# Python with cryptography libraries
pycryptodome
cryptography

- Caesar cipher
- Vigenère cipher  
- Rail Fence cipher
- Substitution ciphers
- Hill cipher
```

### **Symmetric Cryptography (AES)**
**For specific attacks:**
- **AES-CBC Bit-Flipping:** Custom Python
- **AES-ECB:** Python + PyCryptodome
- **AES-CTR:** Python scripts
- **Padding Oracle:** `padding-oracle` tool
- **Side Channel Attacks:** Custom analysis scripts

### **RSA Cryptanalysis**
```yaml
gmpy2
pycryptodome
sympy
factordb-pycli
```
**Specific RSA attacks:**
- **Factorization:** Yafu, Msieve, factordb
- **Common Modulus:** Custom Python
- **Corrupted Keys:** RsaCtfTool
- **Padding Attacks:** Custom Python

### **Advanced Tools**
```yaml
# Comprehensive CTF tool
https://github.com/Ganapati/RsaCtfTool.git

# Factorization tools
yafu
msieve

# LFSR analysis
numpy  # for linear algebra
```

### **Specialized Tools by Challenge Type**

#### **DSA/ECDSA Implementation Errors**
```yaml
ecdsa
gmpy2
```

#### **Shamir Secret Sharing**
```yaml
sssa
```

#### **Stream Ciphers & PRNG**
```yaml
randcrack  # for MT19937 prediction
```

#### **Elliptic Curve Cryptography**
```yaml
ecpy
tinyec
```

#### **Block Cipher Cryptanalysis**
```yaml
sageMath  # for advanced math
# For FEAL, AES weakened variants
```

### **Programming Environment Setup**
```yaml
# Essential Python packages
pycryptodome
gmpy2
sympy
numpy
requests
pwntools
z3-solver
  
# System tools
john
hashcat
binwalk
steghide
exiftool
wireshark
tshark
```

### **Online Resources**
1. **[CyberChef](https://gchq.github.io/CyberChef/)** - web-based crypto operations
2. **[dCode.fr](https://dCode.fr/)** - cipher identification & solving
3. **[FactorDB](https://factordb.com/)** - RSA factorization database
4. **[HashKiller](https://hashkiller.io/)** - hash lookup
5. **[CrackStation](https://crackstation.net/)** - hash cracking database