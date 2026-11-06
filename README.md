# networktalks-week1-cybersecurity-lab
Week 1 – Cybersecurity Internship Practical Lab: Kali Linux and VirtualBox environment setup.
# NetworkTalks – Week 1 Cybersecurity Lab

## Overview

This repository documents the practical lab environment setup completed as part of my cybersecurity internship with NetworkTalks.

The objective was to prepare a Kali Linux virtual machine using Oracle VirtualBox and configure the network, connectivity, and file-sharing features required for the lab environment.

## Lab Environment

| Component | Configuration |
|---|---|
| Host OS | Windows |
| Virtualization | Oracle VirtualBox |
| Guest OS | Kali Linux |
| Network mode | NAT Network |
| NAT Network name | NatNetwork |
| Network subnet | `10.0.0.0/24` |
| Kali IPv4 address | `10.0.0.2/24` |
| Default gateway | `10.0.0.1` |
| DNS server | `8.8.8.8` |

## Tasks Completed

- Set up Kali Linux in Oracle VirtualBox.
- Created a dedicated NAT Network.
- Configured a static IPv4 address for Kali Linux.
- Configured the default gateway and DNS server.
- Enabled bidirectional shared clipboard.
- Enabled bidirectional drag and drop.
- Configured a shared folder between Windows and Kali Linux.
- Tested shared-folder access.
- Tested network and Internet connectivity.
- Created a VirtualBox snapshot of the configured environment.

## Network Configuration

| Parameter | Value |
|---|---|
| IPv4 address | `10.0.0.2` |
| Subnet mask | `255.255.255.0` |
| Prefix | `/24` |
| Gateway | `10.0.0.1` |
| DNS | `8.8.8.8` |

## Shared Folder

A Windows host folder was shared with Kali Linux.

- Host folder: `C:\Cybersecurity-Lab\Downloads`
- Shared folder name: `Downloads`
- Kali mount point: `/media/sf_Downloads`

A test file was created on Windows and successfully read from Kali Linux to verify file-sharing functionality.

## Evidence

Screenshots documenting the configuration and verification steps are available in the [`evidence/`](evidence/) directory.

## Snapshot

A VirtualBox snapshot was created to preserve the configured Kali Linux lab environment.

## Scope

This practical work focuses on virtual lab preparation, network configuration, connectivity testing, and file-sharing validation. It does not represent a production network deployment or an authorization to test external systems.

---

**Program:** Cybersecurity Internship  
**Organization:** NetworkTalks  
**Lab:** Week 1 – Practical Lab Environment Setup
