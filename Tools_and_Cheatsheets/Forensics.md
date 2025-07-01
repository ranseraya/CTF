# CTF Digital Forensics Cheatsheet

*List commands, tips, tools, techniques and guide for digital forensic in CTF*

---

## Table of Contents
- [General File Analysis](#general-file-analysis)
- [Steganography](#steganography)
- [Image File Analysis](#image-file-analysis)
- [Audio File Analysis](#audio-file-analysis)
- [Network Forensics (PCAP)](#network-forensics-pcap)
- [Memory Forensics](#memory-forensics)
- [Filesystem Forensics](#filesystem-forensics)
- [Other Useful Tools](#other-useful-tools)

---

### 1. General File Analysis
    file [file_name]
    strings [file_name] + grep [strings]
    (hex analis use hexedit, xxd, bless, HxD) -> xxd [file_name]
    binwalk [file_name]
        --run-as=root
        -D '.*'
    foremost [file_name]
    

### 2. Steganography

### 3. Image File Analysis
### 4. Audio File Analysis
### 5. Network Forensics 
### 6. Filesystem Forensics
### 7. Other Useful Tools