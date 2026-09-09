# CompTIA Security+ (SY0-701) — Exam Objectives

Study tracker for the five exam domains. Official objectives PDF: [comptia.org](https://www.comptia.org/certifications/security)

| Domain | Weight |
|---|---|
| 1.0 General Security Concepts | 12% |
| 2.0 Threats, Vulnerabilities, and Mitigations | 22% |
| 3.0 Security Architecture | 18% |
| 4.0 Security Operations | 28% |
| 5.0 Security Program Management and Oversight | 20% |

---

## 1.0 General Security Concepts — 12%

- [ ] **Control categories** — technical, managerial, operational, physical
- [ ] **Control types** — preventive, deterrent, detective, corrective, compensating, directive
- [ ] **CIA triad** — confidentiality, integrity, availability; plus non-repudiation
- [ ] **AAA** — authentication, authorization, accounting; authenticating people vs. systems
- [ ] **Zero trust** — control plane vs. data plane, policy engine, policy enforcement point
- [ ] **Physical security** — bollards, vestibules, fencing, surveillance, badges, sensors
- [ ] **Deception & disruption** — honeypots, honeynets, honeyfiles, honeytokens
- [ ] **Change management** — approval, impact analysis, backout plans, maintenance windows, version control
- [ ] **PKI** — public/private keys, key escrow, certificates, CRLs, OCSP, CSRs
- [ ] **Cryptography** — encryption levels, symmetric vs. asymmetric, hashing, salting, digital signatures, key stretching, blockchain
- [ ] **Obfuscation** — steganography, tokenization, data masking

## 2.0 Threats, Vulnerabilities, and Mitigations — 22%

- [ ] **Threat actors** — nation-state, unskilled attacker, hacktivist, insider threat, organized crime, shadow IT
- [ ] **Motivations** — data exfiltration, espionage, service disruption, blackmail, financial gain, revenge, war
- [ ] **Threat vectors** — message-based, image/file-based, voice call, removable device, unsecure networks, open ports, default credentials, supply chain
- [ ] **Social engineering** — phishing, vishing, smishing, pretexting, watering hole, BEC, typosquatting, impersonation
- [ ] **Vulnerabilities** — application, OS-based, web-based (SQLi, XSS), hardware, virtualization, cloud, supply chain, cryptographic, misconfiguration, mobile, zero-day
- [ ] **Malware** — ransomware, trojan, worm, spyware, bloatware, virus, keylogger, logic bomb, rootkit
- [ ] **Network attacks** — DDoS (amplified/reflected), DNS attacks, wireless, on-path, credential replay
- [ ] **Application attacks** — injection, buffer overflow, replay, privilege escalation, forgery, directory traversal
- [ ] **Crypto & password attacks** — downgrade, collision, birthday, spraying, brute force
- [ ] **Indicators** — account lockout, impossible travel, resource consumption, out-of-cycle logging, missing logs
- [ ] **Mitigations** — segmentation, access control, allow lists, isolation, patching, encryption, least privilege, decommissioning
- [ ] **Hardening** — endpoint protection, host-based firewall/HIPS, disabling ports, default password changes

## 3.0 Security Architecture — 18%

- [ ] **Architecture models** — cloud, IaC, serverless, microservices, on-premises, centralized vs. decentralized, containerization, virtualization
- [ ] **Specialized systems** — IoT, ICS/SCADA, RTOS, embedded systems
- [ ] **Considerations** — availability, resilience, cost, scalability, risk transference, patch availability, power, compute
- [ ] **Infrastructure** — device placement, security zones, attack surface, failure modes, active vs. passive, inline vs. tap
- [ ] **Appliances** — jump server, proxy, IPS/IDS, load balancer, sensors
- [ ] **Firewalls** — WAF, UTM, NGFW, Layer 4 vs. Layer 7
- [ ] **Secure communication** — VPN, remote access, tunneling (TLS, IPSec), SD-WAN, SASE
- [ ] **Data types & classifications** — regulated, trade secret, IP; sensitive, confidential, public, restricted, private, critical
- [ ] **Data states** — at rest, in transit, in use; sovereignty and geolocation
- [ ] **Securing data** — encryption, hashing, masking, tokenization, obfuscation, segmentation, permission restrictions
- [ ] **Resilience** — high availability, load balancing vs. clustering, hot/cold/warm sites, geographic dispersion
- [ ] **Backups & power** — onsite/offsite, frequency, snapshots, replication, journaling; generators and UPS

## 4.0 Security Operations — 28%

- [ ] **Secure baselines** — establish, deploy, maintain
- [ ] **Hardening targets** — mobile, workstations, switches, routers, cloud, servers, ICS/SCADA, RTOS, IoT
- [ ] **Mobile solutions** — MDM, BYOD/COPE/CYOD, connection methods
- [ ] **Wireless security** — WPA3, RADIUS, cryptographic and authentication protocols, site surveys, heat maps
- [ ] **Application security** — input validation, secure cookies, static code analysis, code signing, sandboxing
- [ ] **Asset management** — acquisition, ownership, classification, inventory, sanitization, destruction, data retention
- [ ] **Vulnerability management** — scans, threat feeds, OSINT, pen testing, bug bounty, CVSS, CVE, exposure factor
- [ ] **Remediation** — patching, insurance, segmentation, compensating controls, exceptions; rescanning and verification
- [ ] **Monitoring & alerting** — log aggregation, alert tuning, quarantine, SCAP, benchmarks, SIEM, DLP, SNMP traps, NetFlow
- [ ] **Enterprise capabilities** — firewall rules, IDS/IPS, web filtering, Group Policy, SELinux, DNS filtering
- [ ] **Email security** — DMARC, DKIM, SPF, gateways
- [ ] **Detection** — file integrity monitoring, NAC, EDR/XDR, user behavior analytics
- [ ] **IAM** — provisioning, identity proofing, federation, SSO (LDAP, OAuth, SAML), attestation
- [ ] **Access controls** — mandatory, discretionary, role-based, rule-based, attribute-based, time-of-day, least privilege
- [ ] **MFA & passwords** — biometrics, tokens, security keys, the four factors; password policy, managers, passwordless
- [ ] **PAM** — just-in-time permissions, password vaulting, ephemeral credentials
- [ ] **Automation** — provisioning, guard rails, ticket creation, CI/testing, APIs; benefits and technical debt
- [ ] **Incident response** — preparation, detection, analysis, containment, eradication, recovery, lessons learned (know the order)
- [ ] **Forensics** — legal hold, chain of custody, acquisition, preservation, e-discovery
- [ ] **Investigations** — firewall, application, endpoint, OS, IPS/IDS logs; packet captures, dashboards

## 5.0 Security Program Management and Oversight — 20%

- [ ] **Governance** — guidelines, policies, standards, procedures, playbooks
- [ ] **Governance structures** — boards, committees, government entities, centralized vs. decentralized
- [ ] **Roles** — owners, controllers, processors, custodians/stewards
- [ ] **Risk process** — identification, assessment, analysis, register, tolerance, appetite
- [ ] **Quantitative risk** — SLE, ALE, ARO, exposure factor (memorize the formulas)
- [ ] **Risk strategies** — transfer, accept, avoid, mitigate; exemptions vs. exceptions
- [ ] **BIA** — RTO, RPO, MTTR, MTBF
- [ ] **Third-party risk** — vendor assessment, due diligence, conflict of interest, monitoring, rules of engagement
- [ ] **Agreements** — SLA, MOA, MOU, MSA, WO/SOW, NDA, BPA
- [ ] **Compliance** — internal/external reporting, fines, sanctions, reputational damage, loss of license
- [ ] **Privacy** — legal implications, data subject, controller vs. processor, retention, right to be forgotten
- [ ] **Audits & assessments** — attestation, internal vs. external, independent third-party audit
- [ ] **Penetration testing** — physical, offensive, defensive, integrated; known/partially known/unknown environment; passive vs. active recon
- [ ] **Security awareness** — phishing campaigns, anomalous behavior, user guidance, insider threat, reporting and monitoring

---

> Domain 4 is the heaviest at 28%, and domains 4 and 5 together are nearly half the exam. Security+ leans conceptual, so the acronyms and the exact ordering of processes (incident response, risk management) are what get tested directly.
