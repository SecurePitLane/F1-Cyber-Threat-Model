# 🧠 F1 Cyber Threat Model

This project outlines a threat model for a Formula One team's digital infrastructure. It breaks down possible threat actors, attack vectors, and mitigations based on common real-world frameworks like STRIDE and MITRE ATT&CK.

---

## 🏁 Scenario

You’re part of the cybersecurity team for a Formula One organization. The team relies on secure, high-speed data systems for everything from car telemetry and pit-to-garage communication to remote race strategy operations.

Threat modeling helps you stay ahead of adversaries by thinking like one — and proactively identifying where your systems are most vulnerable.

---

## 🎯 Objectives

- Identify key threat actors targeting F1 teams
- Map potential attack surfaces across digital and physical systems
- Align threats with STRIDE and MITRE ATT&CK frameworks
- Suggest high-level mitigations

---

## 🔎 Threat Modeling Overview

| STRIDE Category | Example Threats |
|-----------------|------------------|
| **Spoofing** | Impersonation of team staff, compromised media credentials |
| **Tampering** | Modified telemetry data or race strategy uploads |
| **Repudiation** | Denial of unauthorized access or configuration changes |
| **Information Disclosure** | Leaked car setup data or race strategy |
| **Denial of Service** | DDoS attack during qualifying or race day |
| **Elevation of Privilege** | Unauthorized access to pit lane comms or cloud dashboards |

---

## 👤 Threat Actors

| Actor Type | Motivation | Risk Level |
|------------|------------|------------|
| Nation-state hackers | Espionage, economic advantage | 🔴 High |
| Competing teams (insider threats) | Competitive advantage | 🔴 High |
| Hacktivists | Disruption or protest | 🟠 Medium |
| Script kiddies / hobbyists | Reputation or curiosity | 🟡 Low |
| Disgruntled former employees | Revenge or sabotage | 🔴 High |

---

## 🖥️ Attack Surfaces

- Car telemetry streams (wireless)
- Race strategy dashboards (cloud-based)
- Internal comms (VoIP, radio, Wi-Fi)
- Media guest access points
- Developer backdoors (test tools left open)
- OTA firmware update channels

---

## 🔐 Mitigation Ideas

- Role-based access controls (RBAC)
- Full-packet inspection on sensitive VLANs
- Encrypted and signed telemetry/data streams
- Air-gapped storage for backups & race strategy archives
- Red-team simulations and tabletop incident drills
- Identity verification for all paddock access points

---

## 📌 Why It Matters

Formula One teams are high-profile targets dealing with massive intellectual property, time-sensitive data, and millions in real-time decisions. Modeling threats now prevents compromise later.

---

🚧 *Work in progress. Part of a cybersecurity portfolio focused on protecting high-performance sports organizations.*

