# Snort IDS Implementation Project

## Overview
Complete implementation of a Network Intrusion Detection System (NIDS) using Snort on Raspberry Pi 5, focusing on pentest activity monitoring and network security.

## 🚀 Features
- Dual interface monitoring (regular + promiscuous)
- Custom rule set for pentest activity detection
- Advanced threat detection capabilities
- Performance-optimized configuration

## 🛠️ Technical Environment
- Raspberry Pi 5
- Snort 2.9.20
- DAQ 2.0.7
- Debian-based Linux OS

## 📋 Prerequisites
- Raspberry Pi 5
- Two network interfaces (one with promiscuous mode support)
- Debian-based Linux OS
- Root access

## 🔧 Installation

### Quick Start

git clone https://github.com/[your-username]/snort-ids-implementation.git
cd snort-ids-implementation
sudo ./scripts/install.sh


### Detailed Installation
See [Installation Guide](docs/installation.md) for complete setup instructions.

## 📊 Key Features Implemented

### Network Monitoring
- Dual interface monitoring
- Promiscuous mode support
- Custom traffic analysis

### Detection Capabilities
- Port scanning detection
- Service enumeration monitoring
- Advanced attack pattern recognition
- Pentest tool detection

### Custom Rules
- Specialized pentest activity detection
- Advanced evasion technique monitoring
- Zero-day attack pattern detection

## 📚 Documentation

- [Installation Guide](docs/installation.md)
- [Configuration Guide](docs/configuration.md)
- [Rules Documentation](docs/rules.md)
- [Troubleshooting Guide](docs/troubleshooting.md)


### System Setup
![Setup Diagram](images/setup-diagram.png)

### Alert Examples
![Alert Examples](images/alerts-example.png)

## 👤 Author
**d3nkers**
- GitHub: [@d3nkers](https://github.com/yourusername)

## 🌟 Acknowledgments
- Inspiration for my own experience and understanding what enumeration tools cause at the other end of the line
