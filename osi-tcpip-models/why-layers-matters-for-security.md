# Why Network Layers Matter for Security

Network layers exist so that complex communication can be controlled, analyzed, and secured in a structured way.  
Each layer handles a specific part of data transmission, and each layer can be attacked or defended independently.

Understanding layers allows security teams to **locate threats, apply controls, and stop attacks at the right point**.

---

## Security Works by Layer

Every cyber-attack moves through layers.  
Firewalls, antivirus software, IDS, and encryption all operate at different layers.

If one layer fails, others can still protect the system.

This is called **defense in depth**.

---

## Physical and Data Link Layers (OSI Layer 1–2)

These layers handle cables, Wi-Fi, switches, and MAC addresses.

Threats:
- Rogue devices plugged into the network
- Wi-Fi eavesdropping
- ARP spoofing
- Packet sniffing

Security controls:
- Port security
- MAC filtering
- Network segmentation (VLANs)
- Wi-Fi encryption

If these layers are weak, attackers can access the network before any firewall sees them.

---

## Network Layer (OSI Layer 3)

This layer controls IP addressing and routing.

Threats:
- IP spoofing
- Routing attacks
- Network scanning
- DDoS

Security controls:
- Firewalls
- IP filtering
- VPNs
- Routing authentication

This layer controls **who can reach what network**.

---

## Transport Layer (OSI Layer 4)

This layer manages ports and connections.

Threats:
- Port scanning
- Session hijacking
- Flooding attacks

Security controls:
- Stateful firewalls
- Port filtering
- IDS/IPS

This layer protects **how data sessions are created and maintained**.

---

## Application Layer (OSI Layer 7)

This is where users interact with systems.

Threats:
- Web hacking
- Malware
- Phishing
- Data theft

Security controls:
- Web application firewalls
- Antivirus
- Authentication
- Encryption

Most real-world breaches happen here.

---

## Why This Matters

Without layers:
- Security tools would be blind
- Attacks would be harder to detect
- Defenses would be ineffective

Layers allow:
- Precise security control
- Clear attack detection
- Better incident response

---

## Final Insight

Hackers move **through layers**.  
Defenders block **at layers**.

If you understand the layers, you understand how to **stop attackers instead of just reacting to them**.
