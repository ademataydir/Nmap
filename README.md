# What is Nmap and How to Use It?

## 🔍 What is Nmap?

**Nmap (Network Mapper)** is a free and open-source network scanning tool. It is widely used by system administrators and cybersecurity professionals to:

- Discover devices on a network (host discovery)  
- Detect open ports (port scanning)  
- Identify running services and versions (service/version detection)  
- Gather operating system information (OS detection)  
- Perform vulnerability assessments

Nmap ranges from being a simple IP scanner to a powerful tool for in-depth security auditing.

## ⚙️ How to Use Nmap?

Nmap is typically used via the command line. Basic syntax:

```
nmap [options] <target IP or domain>
```

### 🔧 Basic Commands:

| Purpose                             | Command Example                     |
|-------------------------------------|-------------------------------------|
| Simple port scan                    | `nmap 192.168.1.1`                  |
| Scan all ports                      | `nmap -p- 192.168.1.1`              |
| Detect services and versions        | `nmap -sV 192.168.1.1`              |
| Identify operating system           | `nmap -O 192.168.1.1`               |
| Fast scan                           | `nmap -T4 192.168.1.1`              |
| Default script scan                 | `nmap -sC 192.168.1.1`              |
| Scan specific ports                 | `nmap -p 22,80,443 192.168.1.1`     |


## 📈 Use Cases for Nmap

- Penetration testing  
- Asset discovery in SOC and Blue Team operations  
- Investigating suspicious activity  
- Evaluating security posture through open ports and services
