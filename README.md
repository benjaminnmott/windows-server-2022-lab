# Windows Server 2022 Virtual Lab (VirtualBox)

## Overview
This project documents the deployment and configuration of a Windows Server 2022 virtual lab using Oracle VirtualBox. The lab was built to demonstrate hands-on experience with virtualization, Windows Server installation, role-based configuration, and service validation in a controlled environment.

## Environment
- Host OS: Windows 10/11
- Hypervisor: Oracle VirtualBox
- Guest OS: Windows Server 2022 (Desktop Experience)
- CPU: 2 vCPUs
- RAM: 4 GB
- Storage: SATA (VDI)
- Networking: NAT + Host-Only Adapter

---

## Virtual Machine Configuration

![VirtualBox VM Overview](screenshots/01-virtualbox-vm-overview.png)

This screenshot shows the VirtualBox configuration for the Windows Server 2022 virtual machine, including resource allocation, EFI-enabled boot mode, SATA storage controller configuration, mounted installation ISO, and dual network adapters used for internet access and internal lab networking.

---

## Server Installation & Initial Setup

![Server Manager Dashboard](screenshots/04-server-manager-dashboard.png)

After installation, Server Manager was used to verify that the server was operational and manageable. The dashboard confirms successful deployment and provides access to system health, role management
