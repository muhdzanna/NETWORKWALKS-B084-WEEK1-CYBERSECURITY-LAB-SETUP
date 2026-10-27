# NetworkWalks Week 1: Cybersecurity Lab Setup

## Project Overview
This project documents my Week 1 cybersecurity lab setup using Oracle VirtualBox and Kali Linux.

## Objectives
- Set up a Kali Linux virtual machine.
- Configure and inspect network settings.
- Test internet connectivity and DNS resolution.
- Create a virtual machine snapshot.

## Tools Used
- Oracle VirtualBox
- Kali Linux
- Linux Terminal
- GitHub

## Network Connectivity Tests
I used the following commands to verify connectivity:

```bash
ip -br addr
ip route
ping -c 4 8.8.8.8
ping -c 4 google.com
```

**Observed results:** Both connectivity tests returned 4 replies with 0% packet loss, and DNS resolution for `google.com` succeeded.

## Screenshots
Project evidence is available in the [`screenshots`](./screenshots/) folder:
- `kali-network-configuration.png`
- `network-connectivity-dns.png`

## Key Learnings
- Working with a Kali Linux virtual machine.
- Inspecting IP addresses and routing information.
- Testing network connectivity and DNS resolution.
- Documenting practical cybersecurity work using GitHub.

## Challenges
I encountered virtual machine networking and screenshot-transfer difficulties during setup. I worked through the process and uploaded my evidence to GitHub.

## Disclaimer
This repository documents a beginner cybersecurity lab for educational purposes.
