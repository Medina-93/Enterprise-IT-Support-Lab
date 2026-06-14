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

### [Insert Your Command Prompt Screenshot Here]

---

## Phase 2: Live Enterprise Ticket Lifecycle Triage
Deployed an IT Service Management dashboard inside Jira Service Management. Successfully claimed, tracked, documented, and fully resolved a critical tier-1 support incident following standard operating procedures (SOPs).

*   **Incident Subject:** Remote Worker experiencing total internet drop when launching corporate VPN.
*   **Root Cause Analysis:** Verified that local client routing tables were failing upon launching the secure tunnel due to a metric overwrite error (Split-Tunneling mismatch configuration).
*   **Resolution Protocol:** Reinstalled a verified clean AnyConnect profile configuration, flushed local system routing tables, and confirmed connection stability before marking the ticket as resolved in the open work queue.
![https://github.com/Medina-93/Enterprise-IT-Support-Lab/blob/main/Screen%20Shot%202026-06-14%20at%204.04.41%20PM.png?raw=true

