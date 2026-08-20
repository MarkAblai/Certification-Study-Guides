# CompTIA Network+ (N10-009) — Exam Objectives

Study tracker for the five exam domains. Official objectives PDF: [comptia.org](https://www.comptia.org/certifications/network)

| Domain | Weight |
|---|---|
| 1.0 Networking Concepts | 23% |
| 2.0 Network Implementation | 20% |
| 3.0 Network Operations | 19% |
| 4.0 Network Security | 14% |
| 5.0 Network Troubleshooting | 24% |

---

## 1.0 Networking Concepts — 23%

- [ ] **OSI model** — all seven layers, and what lives where
- [ ] **Appliances** — routers, switches, firewalls, IDS/IPS, load balancers, proxies, NAS/SAN, wireless controllers
- [ ] **Cloud** — NFV, VPCs, security groups, cloud gateways; public/private/hybrid; SaaS/IaaS/PaaS
- [ ] **Ports & protocols** — FTP, SFTP, SSH, Telnet, SMTP, DNS, DHCP, HTTP/S, SNMP, LDAP, RDP, SIP
- [ ] **Traffic types** — unicast, multicast, anycast, broadcast
- [ ] **Media** — 802.11, cellular, satellite; fiber, coax, DAC
- [ ] **Transceivers & connectors** — SC, LC, ST, MPO, RJ11, RJ45, F-type, BNC
- [ ] **Topologies** — mesh, hybrid, star/hub-and-spoke, spine-and-leaf, point-to-point, three-tier, collapsed core
- [ ] **IPv4 addressing** — public vs. private, RFC1918, APIPA, loopback, classes A–E
- [ ] **Subnetting** — VLSM and CIDR (practice until it's fast, this is where the time goes)

## 2.0 Network Implementation — 20%

- [ ] **Routing** — static vs. dynamic; BGP, EIGRP, OSPF; route selection
- [ ] **Address translation** — NAT, PAT, FHRP, VIPs, subinterfaces
- [ ] **Switching** — VLANs, interface config, spanning tree, MTU, jumbo frames
- [ ] **Wireless** — channels, frequencies, SSIDs, encryption, guest networks, authentication, antennas, APs
- [ ] **Physical installs** — power draw, environmental factors, installation constraints

## 3.0 Network Operations — 19%

- [ ] **Documentation** — physical vs. logical diagrams, rack diagrams, cable maps, asset inventory, IPAM, SLAs, wireless surveys
- [ ] **Life cycle** — EOL, EOS, software management, decommissioning
- [ ] **Change & config management** — request tracking; production, backup, and baseline configs
- [ ] **Monitoring** — SNMP, flow data, packet capture, baselines, log aggregation, API integration, port mirroring
- [ ] **Disaster recovery** — RPO, RTO, MTTR, MTBF; cold/warm/hot sites; active-active vs. active-passive; testing
- [ ] **Network services** — DHCP, SLAAC, DNS, NTP, PTP, NTS
- [ ] **Access & management** — VPN, SSH, GUI, API, console

## 4.0 Network Security — 14%

- [ ] **Logical security** — encryption in transit and at rest, PKI, IAM, MFA, SSO
- [ ] **AAA protocols** — RADIUS, LDAP, SAML, TACACS+; authorization, least privilege, RBAC, geofencing, time-based auth
- [ ] **Physical security** — cameras, locks
- [ ] **Deception tech** — honeypots, honeynets
- [ ] **Terminology** — risk, vulnerability, exploit, threat, CIA triad
- [ ] **Audits & compliance** — data locality, PCI DSS, GDPR
- [ ] **Segmentation** — IoT, IIoT, SCADA, ICS, OT, guest, BYOD
- [ ] **Attacks** — DoS/DDoS, VLAN hopping, MAC flooding, ARP and DNS poisoning, rogue devices, evil twin, on-path
- [ ] **Social engineering** — phishing, dumpster diving, shoulder surfing, tailgating
- [ ] **Defenses** — device hardening, NAC, key management, ACLs, URL/content filtering, trusted vs. untrusted zones, screened subnets

## 5.0 Network Troubleshooting — 24%

- [ ] **Methodology** — identify, theorize, test, plan, implement, verify, document (know the order; it's tested directly)
- [ ] **Cabling & interfaces** — wrong cable type, signal degradation, bad termination, TX/RX transposed; port status and error counters
- [ ] **Hardware** — PoE budget, transceiver mismatch, signal strength
- [ ] **Switching issues** — STP, VLAN assignment, ACLs
- [ ] **Routing issues** — routing table problems, missing default routes
- [ ] **Addressing issues** — pool exhaustion, wrong gateway/IP/subnet mask
- [ ] **Performance** — congestion, latency, packet loss, wireless interference
- [ ] **Tools** — protocol analyzers, CLI tools, cable testers, Wi-Fi analyzers

---

> Domain 5 is the heaviest at 24%, and it's the one you can't cram — it rewards hands-on time. Domains 1 and 5 together are nearly half the exam.
