# Enterprise IT Support & Network Diagnostics Sandbox

## Project Overview
Designed, deployed, and configured a multi-platform virtualization environment to simulate an enterprise corporate technical support pipeline. This project demonstrates foundational Tier 1 Help Desk capabilities, active incident lifecycle management, and core Layer 3 network troubleshooting methodology.

## Technical Skills & Tools Used
*   **Hypervisor:** Oracle VirtualBox 7.0 (Hosted on macOS Catalina Intel architecture)
*   **Guest Client:** Windows 10 Pro (Configured with 2GB RAM, 30GB Preallocated Storage)
*   **Ticketing & ITSM Platform:** Jira Service Management Cloud (Company-Managed Architecture)
*   **Network Diagnostics Suite:** Command Prompt (`ipconfig /all`, `ping`, `nslookup`)

---

## Phase 1: Virtual Infrastructure & Network Baseline
Successfully bypassed legacy macOS hardware resource constraints by utilizing fixed-disk preallocation storage parameters within VirtualBox to host a functional corporate client simulation profile. 

Executed standard diagnostic commands within the Windows environment to verify local network configuration and confirm external outbound connectivity:
*   `ipconfig /all` - Verified active DHCP lease agreements and identified local default gateway paths.
*   `ping 8.8.8.8` - Confirmed structural Layer 3 stability with 0% data packet loss and steady latency bounds.
*   `nslookup google.com` - Validated Domain Name System (DNS) server configuration routing metrics.


---

## Phase 2: Live Enterprise Ticket Lifecycle Triage
Deployed an IT Service Management dashboard inside Jira Service Management. Successfully claimed, tracked, documented, and fully resolved a critical tier-1 support incident following standard operating procedures (SOPs).

*   **Incident Subject:** Remote Worker experiencing total internet drop when launching corporate VPN.
*   **Root Cause Analysis:** Verified that local client routing tables were failing upon launching the secure tunnel due to a metric overwrite error (Split-Tunneling mismatch configuration).
*   **Resolution Protocol:** Reinstalled a verified clean AnyConnect profile configuration, flushed local system routing tables, and confirmed connection stability before marking the ticket as resolved in the open work queue.
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/97f72a9d-9cda-4f4a-a263-3b81b7342fa2" />
<img width="1956" height="1020" alt="image" src="https://github.com/user-attachments/assets/f577d48f-00a7-4cf2-a531-4d9d7a65f8ce" />
<img width="1956" height="1020" alt="image" src="https://github.com/user-attachments/assets/96eeb4cf-d9d1-440f-a9f1-4558d8a5d498" />
<img width="1956" height="1020" alt="image" src="https://github.com/user-attachments/assets/9b98dceb-e8c5-4a1d-bf88-fd9f937bf917" />
<img width="2202" height="1422" alt="image" src="https://github.com/user-attachments/assets/cd4224e7-7567-466b-9737-38d104498a38" />
<img width="2832" height="1534" alt="image" src="https://github.com/user-attachments/assets/20474a99-710d-4b85-9c41-0f5ceb269f26" />
<img width="2846" height="1538" alt="image" src="https://github.com/user-attachments/assets/42b9cb81-1773-478c-bcd6-8d84eb11dad7" />
<img width="2850" height="1532" alt="image" src="https://github.com/user-attachments/assets/3515323d-f793-4ec4-b2c1-cb328fe260be" />
<img width="2862" height="1542" alt="image" src="https://github.com/user-attachments/assets/49aecd35-f6f5-4d5f-8cb8-c99e4fa68445" />

