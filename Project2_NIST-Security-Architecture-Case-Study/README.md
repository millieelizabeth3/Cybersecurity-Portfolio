# Security Architecture & Risk-Based Design (NIST Framework)

## Overview
This repository presents a security architecture and risk-based design for a fictional Department of Defense (DoD)-aligned organization, Blue Stripe Tech, as it prepares to support a major contract with the U.S. Air Force Cyber Security Center.

The objective of this case study was to design a secure, compliant IT environment aligned with DoD and federal cybersecurity requirements while balancing operational needs, risk tolerance, and regulatory constraints. The project emphasizes security architecture, governance, and control selection rather than tool-specific implementation.

This case study demonstrates how NIST guidance, DoD directives, and risk management principles can be translated into a cohesive, real-world security design.

---

## Problem Statement
Blue Stripe Tech is entering into a contract that requires strict compliance with Department of Defense cybersecurity requirements. As a federal contractor handling sensitive government data, the organization must establish a security architecture that protects systems and information while maintaining operational efficiency.

Key challenges included:
- Protecting sensitive and controlled unclassified information (CUI)
- Meeting mandatory federal and DoD cybersecurity requirements
- Designing layered security controls across multiple infrastructure domains
- Balancing security enforcement with mission continuity and usability

---

## Organizational Context & Assumptions
- Organization type: DoD-aligned federal contractor (fictional)
- Regulatory environment: DoD and NIST-based cybersecurity requirements
- Threat landscape:
  - Advanced persistent threats (APT)
  - Insider risk
  - Unauthorized access and data exfiltration
- Constraints:
  - Budget and scalability considerations
  - Need for continuous operations
  - Integration with DoD systems and partners

These assumptions were used to guide control selection and architectural decisions throughout the design.

---

## Laws, Directives, & Compliance Drivers
The security design was shaped by the following primary compliance requirements:

- **FISMA** – Establishes mandatory information security programs for federal agencies and contractors
- **DFARS 252.204-7012** – Requires protection and incident reporting for Covered Defense Information
- **CMMC 2.0** – Defines cybersecurity maturity expectations for defense contractors
- **Executive Order 13556 (CUI)** – Governs the handling and protection of controlled unclassified information
- **DoD Instruction 8510.01 (RMF)** – Provides the risk management lifecycle for DoD information systems

These requirements collectively informed the architecture, control selection, and governance approach.

---

## Frameworks & Standards Used
- NIST Cybersecurity Framework (CSF)
- NIST SP 800-53 Rev. 5 (Security & Privacy Controls)
- NIST SP 800-171 (Protection of CUI)
- DoD Risk Management Framework (RMF)
- Defense-in-depth principles
- Least privilege and role-based access control (RBAC)

---

## Security Architecture Design

### User Domain
The user domain focuses on minimizing human-related risk through policy enforcement and access control:
- Role-based access control aligned with job responsibilities
- Strong account provisioning and deprovisioning processes
- Multi-factor authentication for privileged and remote access
- Mandatory security awareness and role-based training

---

### Workstation & System Domain
Endpoints and systems are secured using standardized configurations and continuous protection:
- Secure baseline configurations aligned with DISA STIGs
- Centralized patch and vulnerability management
- Anti-malware and endpoint detection controls
- Full-disk encryption for data protection

---

### Network & Perimeter Security
Network security is implemented using layered defenses and segmentation:
- Segmentation of internal networks using VLANs and access controls
- Firewalls and intrusion detection/prevention systems
- Secure LAN-to-WAN boundary protections
- Centralized monitoring and logging for visibility and response

---

### WAN & Remote Access Domains
External connectivity is tightly controlled to protect DoD traffic:
- DoD-approved VPN solutions with multifactor authentication
- FIPS-validated encryption for all external communications
- Prohibition of split tunneling
- Endpoint posture validation prior to granting remote access

---

### System & Application Domain
Applications and systems are secured throughout their lifecycle:
- Secure software development practices
- Compliance with DISA application STIGs
- Role-based access control and least privilege enforcement
- Logging, monitoring, and audit review for accountability

---

## Risk Management Approach
Risk was managed using a structured, risk-based methodology aligned with the DoD RMF. Security controls were selected based on:
- Threat likelihood
- Potential mission and business impact
- Organizational risk tolerance

Priority was placed on mitigating high-impact risks while maintaining system availability and operational effectiveness.

---

## Outcomes & Recommendations
The proposed security architecture:
- Aligns with NIST and DoD cybersecurity expectations
- Reduces attack surface through layered controls
- Improves monitoring, detection, and incident response readiness
- Establishes a scalable foundation for future security maturity

---

## Reflection & Real-World Considerations
In a real-world implementation, additional considerations would include:
- Continuous control assessment and monitoring
- Integration with legacy systems
- Ongoing compliance validation and audits
- Adaptation to evolving threat intelligence

This project strengthened my ability to think systemically about security architecture, governance, and risk trade-offs in regulated environments.

---

## Skills Demonstrated
- Security architecture and design
- Risk assessment and mitigation
- NIST framework application
- DoD compliance awareness
- Technical writing and documentation
- Systems-level security thinking

---

## Appendix
The original academic paper used as the foundation for this case study is available in the `appendix/` directory for reference.
