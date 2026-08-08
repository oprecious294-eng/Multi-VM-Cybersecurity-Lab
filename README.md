# Multi-VM-Cybersecurity-Lab
<h1>simulated network environment</h1>
<p>This document is the authoritative build record for a multi-virtual-machine departmental homelab constructed on Oracle VirtualBox. The lab simulates a segmented enterprise network topology across five organisational departments: Finance, Audit, Information Technology, Procurement, and Guest. It was designed and built by a system administrator to replicate the structure, separation, and management characteristics of a production corporate network in a fully virtualised, consequence-free environment.
: </p>

<p>The lab consists of eighteen virtual machines: four departmental servers running Windows Server 2022, fourteen workstations running Windows 8, and a Guest segment with two workstations and no server. Each department's virtual machines are logically grouped within VirtualBox using the Groups feature, which provides a visual and administrative structure mirroring real-world organisational boundaries. Network isolation is enforced using VirtualBox's Internal Network feature, ensuring that each department's traffic remains within its own broadcast domain.
.</p>

<p>This homelab serves as a practical platform for system administration skill development and demonstration — providing a hands-on environment for practising Active Directory, Group Policy, user management, network configuration, incident simulation, and security hardening without risk to production systems. Every configuration decision documented here reflects the standards and decision-making processes of a professional system administrator.
.</p>
