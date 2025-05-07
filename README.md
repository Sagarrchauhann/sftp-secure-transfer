# Secure File Transfer System using SFTP on Linux

This project demonstrates the setup of a secure file transfer system using **SFTP (Secure File Transfer Protocol)** on a **Linux-based server environment**.

## Project Overview

- **Prepared By:** Sagar Chauhan  
- **Date:** 26-April-2025  
- **Client OS:** Kali Linux  
- **Server OS:** Ubuntu Server 20.04  
- **Virtualization:** Oracle VirtualBox

## Technologies & Tools

- OpenSSH Server
- Chroot Jail for SFTP
- UFW Firewall
- SSH/SFTP Protocols
- Bridged Network Adapter (VirtualBox)

## Configuration Steps

1. Install and enable OpenSSH server
2. Create a restricted SFTP user
3. Set proper directory ownership and permissions
4. Configure chroot jail in SSH config
5. Connect using SFTP and transfer files
6. Verify secure operation with upload/download test

## Security Measures

- Chroot jail to limit user access
- Password authentication
- Disabled port forwarding and X11
- Encrypted communication via SSH

## Testing

- IP connectivity between Kali & Ubuntu
- SFTP login and file transfer verification using `put` and `get`

## Full Documentation

You can view the full detailed documentation in [Developing a Secure File Transfer System Using SFTP on a Linux Server.docx]

---
