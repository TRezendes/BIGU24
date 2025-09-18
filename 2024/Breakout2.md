# Guarding Your Treasure with NIST CSF 2.0

**Arren Soroko** *Information Security Auditor I, BIG*

> The NIST Cybersecurity Framework (CSF) is a set of voluntary guidelines designed to help organizations assess and improve their ability to prevent, detect, and respond to cybersecurity risks. Developed by the U.S. National Institute of Standards and Technology (NIST), the framework was initially published in 2014 for critical infrastructure sectors but has since been widely adopted across various industries, including government and private enterprises globally. The framework integrates existing standards, guidelines, and best practices to provide a structured approach to cybersecurity risk management.
>
> -- Wikipedia [NIST Cybersecurity Framework](https://en.wikipedia.org/wiki/NIST_Cybersecurity_Framework)

## The Evolving Cyber Threat Landscape

### Current Trends in Cyber Threats

- Ransomware Attacks
  - 13% Increase YoY
- Supply Chain Attacks
- Cloud Security Vulnerabilities
- AI-Powered Attacks
  - Improving social engineering attacks
- IoT Vulnerabilities
  - Expanded attack surface *and*…
  - Security weak links
- Zero-Day Exploits

### Impact of Cyber Threats

- Financial Loss
- Reputational Damage
- Operational Disruption
- Legal and Regulatory Consequences
- Intellectual Property Theft

### Importance of a Robust Cybersecurity Strategy

- Risk Mitigation
- Business Continuity
- Customer Trust
- Competitive Advantage
- Regulatory Compliance
- Cost Savings
  - Average cost of data breach $4.45m in 2023 *per IBM*
- Innovation Enablement

## History and Evolution of NIST CSF

- First released in 2014 in response to presidential EO
- Help organizations understand, reduce, and communicate about cybersecurity risk
- Evolution of CSF reflects changing nature of cyber risks
- 2.0, February 2024 - first major revision

### Purpose and Scope of CSF 2.0

- Provide comprehensive and flexible approach to managing cybersecurity risk focusing on:
  - Expanded applicability
  - Risk management focus
  - Standardization and flexibility
  - Improved usability
  - Alignment with international standards

### Key Updates in CSF 2.0

- Addition of "Govern" function
- Expanded scope
  - 1.0 designed for Critical Infrastructure
  - 2.0 more broadly applicable
- Restructured core
- Enhanced guidance
- Improved language and structure
- Focus on emerging technologies

## Core Functions of NIST CSF 2.0

### Govern (GV)

- Provides context for establishing and monitoring risk management by including the following aspects:
  - Organizational Context
  - Risk Management Strategy
  - Roles, Responsibilities, and Authorities
  - Policy
  - Oversight
  - Cybersecurity Supply Chain Risk Management


- Establish a cybersecurity steering committee that meets regularly to review cybersecurity strategy
- Develop an organization wide enterprise risk management plan that identifies and defines cybersecurity roles and responsibilities with the organization
- Create and maintain a list of suppliers and prioritize them based upon the criticality of service provided to the organization


### Identify (ID)

- Focuses on understanding current cybersecurity risks, involving:
  - Asset Management
  - Risk Assessment
  - Improvement


- Implement an automated asset discovery tool to maintain an up-to-date inventory of all hardware and software assets on the network
- Classify document and types and tag data accordingly
- Perform regular vulnerability scanning and document findings and remediations
- Perform regular risk assessments to identify risks and document them according to the impact posed and likelihood of occurrence


### Protect (PR)

- Implementing safeguards to ensure delivery of critical services, involving:
  - Identity Management, Authentication, and Access Control
  - Awareness and Training
  - Data Security
  - Platform Security
  - Technology Infrastructure Resilience


- Deploy multi-factor authentication for all user accounts, especially for privileged access
- Role based access control
- Perform security awareness training for all employees, tracking user acknowledgement and completion
- Windows environment enforcing Bitlocker on all data drives, encrypting external drives, etc.
- Implementing SMB signing
- Implement endpoint detection and response software


### Detect (DE)

- Developing and implementing activities to identify security events, involving:
  - Continuous Monitoring
  - Adverse Event Analysis


- Implement a Security Information and Event Management (SIEM) system to centralize log collection and analysis for anomaly detection
- Document criteria for when security events should be escalated to an incident
- Implement a centralized repository to store logs from multiple sources
- Monitor sensitive areas with surveillance systems


### Respond (RS)

- Taking action regarding a detected cybersecurity incident, involving:
  - Incident Management
  - Incident Analysis
  - …


- Develop and regularly test an Incident Response Plan that outlines roles, responsibilities, and procedures for handling various types of cybersecurity incidents
- Create procedures for evidence collection and preservation when responding to a cyber security incident
- Hold post-incident hot wash to review incident response efforts and improve plan


### Recover (RC)

- Maintaining plans for resilience and restoring any capabilities or services …
  - …


- Conduct regular backup and recovery drills to ensure critical systems and data can be restored within defined objectives
  - 3, 2, 1 backups
  - ***TEST*** backups
- Document a Disaster Recovery plan that includes recovery procedures
 - RPO: Recovery Point Objectives
 - RTO: Recovery Time Objectives


## Implementation of NIST Within Your Organization

### Getting Started

- Utilize NIST Resources and Tools
  - <https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf>
  - <https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.1300.pdf>
- Engage leadership and stakeholders
- Consider supply chain security


### Develop a Cybersecurity Profile

- Conduct a risk assessment
- Analyze existing controls and practices
- Prioritize NIST CSF 2.0 categories based on assessment results
- Customize the framework to fit your organizational needs
- Utilize quick-start guides and implementation examples


### Continuous Improvement and Adaptation

- Implement Governance, Risk, and Compliance (GRC) tool or some other method of GRC tracking (excel, etc.)
  - E.g. [Tentacle](https://tentacle.co)
- Document baseline findings
- Regularly update and refine cybersecurity practices in accordance with NIST CSF 2.0
- Continue to monitor progress over time
