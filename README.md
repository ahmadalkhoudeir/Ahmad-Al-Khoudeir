# Ahmad Al Khoudeir

**Cybersecurity Student | Cyber Defense, Network Security, and AI Security**

**[LinkedIn](https://www.linkedin.com/in/ahmad-a-k-67304131b/)** | **[Email](mailto:a.alkhoudeir@my.ccsu.edu)**

*I'm a cybersecurity student at Central Connecticut State University, working toward a B.S. in Cybersecurity with a Cyber Defense concentration and a minor in AI and Robotics (graduating Spring 2028). Most of what I build sits where network security, compliance, and AI overlap. I'm aiming for a career in government cybersecurity and AI security engineering, so a lot of my current work is about tools that can run offline and hold up to real compliance standards.*

<!-- Optional: add a banner or collage here, the way rshaz2713 does. Good candidates: a Max-Guard dashboard screenshot, the VMware lab network, and a photo from a demo or presentation.
[![GitHub Profile Collage](ahmadalkhoudeir-profile-collage.png)](ahmadalkhoudeir-profile-collage.png)
-->

## Featured Project: Max-Guard

Max-Guard is a network security scanner that checks retail networks against PCI-DSS v4.0. It captures live traffic, flags insecure services like FTP, Telnet, HTTP, POP3, IMAP, and RDP, and turns the findings into a dashboard with severity scores, affected devices, and remediation steps. I served as Security Lead on the student team that built it at CCSU.

- **[Max-Guard Repository](https://github.com/ahmadalkhoudeir/maxguard)** - Python 3.11, Scapy for packet capture, GPT-4o-mini for threat analysis, and a Streamlit dashboard with Plotly charts. Reports export as JSON, CSV, or an executive summary, and the app ships with Docker support.
- **[Live Demo](https://maxguard.streamlit.app)** - The cloud version runs on Streamlit Cloud and works from uploaded scan results, since live capture needs local admin privileges.
- **Lab Testing** - I tested the scanner in a VMware lab with three Ubuntu 22.04 VMs (a scanner, a POS terminal, and a database server) and confirmed it caught real cleartext violations over HTTP, Telnet, and FTP.
- **[Rebuild Application Form](https://github.com/ahmadalkhoudeir/maxguard-student-interest-form)** - We are now rebuilding Max-Guard to replace the external AI API with locally hosted models (Ollama and llama.cpp) so it can run in offline and air-gapped environments. This form is how CCSU students can apply to join the new team.

## In Progress

- **Help Desk Identity Verification Protocol** - A workflow layer that sits around help desk agents and replaces knowledge-based authentication with out-of-band confirmation sent to pre-enrolled channels. It's built around NIST SP 800-63-4, which no longer treats security questions as a valid way to verify someone. The main idea is that a ticket can't be closed without a verification record, and the whole check should take under 30 seconds. ***Repository will be linked once the first version is up.***

## CCSU Coursework and Lab Work

Selected work from my cybersecurity and networking classes:

- **Risk Assessment and Network Activity Scanner** - A NIST-based risk assessment project and a suspicious network activity scanner. *CYS 227 (Introduction to Cybersecurity)*
- **Windows Server Administration Labs** - Active Directory, Group Policy, WSUS, IIS, print services, backup and recovery, and server monitoring. *CET 339 (Windows Server Administration)*
- **Linux Network Administration** - Linux system and network administration, studying toward the CompTIA Linux+ exam. *CET 479 (Network Administration)*
- **Switching, Routing, and Wireless** - Cisco SRWE v7.0 curriculum covering device configuration, switching, routing, and wireless networking.
- **Applied AI** - Prompt engineering, retrieval-augmented generation (RAG) architecture, and using AI to augment business work. *MIS 202*

Frameworks I've worked with hands-on include NIST CSF 2.0 and NIST SP 800-37 (Risk Management Framework).

## Beyond the Code

- I built a website for **Dynamic Decor Painting & Home Services LLC** a Connecticut painting and home improvement contractor. URL: https://dynamicdecorpainting.com/
- I currently work as a Maintenance Tech for Brookdale, where my job includes
  -Performed preventive and corrective maintenance on mechanical, electrical, and facility systems
  -Diagnosed and repaired equipment issues to minimize downtime
  -Interpreted technical manuals, blueprints, and schematics
  -Maintained service logs and ensured OSHA safety compliance
- I worked as an Arabic–English interpreter with **IRIS (Integrated Refugee & Immigrant Services)**.
- I volunteered as a Judge at the VEX IQ Championship, evaluating robotics teams through technical interviews, engineering notebook reviews, and rubric-based scoring. Contributed to fair award selection while promoting STEM education and student innovation.
