## Day 2 - Domain Controller Build

### VM Details
- Name: DC01
- OS: Windows Server 2022
- vCPU: 2
- RAM: 4GB
- Disk: 60GB
- Network: NAT

### Actions Completed
- Installed Windows Server 2022
- Renamed the host to DC01

### Notes
- AD DS not installed just yet
- System prepped for domain promotion

### Whats the role of a domain controller?
- A DC is a server that processes authentication from users and computers within a domain
- most commonly used in Windows AD domains

### Why do we isolate lab networks?
- To keep it separate and secure from the host network
- so we don't accidentally violate security policies on the host network

