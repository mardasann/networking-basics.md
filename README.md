# Networking Basics – Day 2

## What I learned
Today I reviewed core networking concepts that are fundamental in cybersecurity.

### IP Address
An IP address identifies a device on a network.  
Local IP addresses (e.g. 192.168.x.x) are used inside private networks, while public IPs are exposed to the internet.

From a security perspective, every attack starts with identifying a target IP.

### Ports
Ports represent entry points for services running on a system.  
Each open port increases the attack surface.

Common ports:
- 80 – HTTP
- 443 – HTTPS
- 22 – SSH
- 21 – FTP

If a port is open, it means a service is listening and must be secured.

### TCP vs UDP
TCP is connection-oriented and reliable, while UDP is faster but connectionless.  
Understanding this difference is important when analyzing network traffic and scans.

### DNS
DNS translates domain names into IP addresses.  
Because of this, DNS is a common target for attacks such as spoofing or poisoning.

## Security Perspective
A system is only as secure as the services it exposes.  
Open ports and running services define the attack surface.

## Next Step
Move on to Linux networking commands and basic enumeration techniques.
