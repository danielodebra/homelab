<div align="center">

🖥️ My Homelab

Linux · Virtualisation · Self-Hosting · Infrastructure

An evolving home lab built with repurposed hardware, virtual machines and self-hosted applications.

</div>

⸻

👋 About the Project

My homelab started with an old Acer Aspire laptop that I brought back to life and turned into a Linux server.

Since then, I’ve added a Dell OptiPlex running Proxmox VE, Linux and Windows virtual machines, additional storage and a collection of self-hosted applications.

I use it to experiment with technology, troubleshoot problems and learn by building things myself.

Build it. Run it. Break it. Fix it. Learn from it.

⸻

🏗️ Infrastructure at a Glance

<table>
  <thead>
    <tr>
      <th>🖥️ Dell OptiPlex</th>
      <th>💻 Acer Aspire</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        <strong>Main Virtualisation Server</strong>
        <ul>
          <li>Proxmox VE</li>
          <li>Ubuntu Server VM</li>
          <li>Windows Server VM</li>
          <li>Windows 11 VM</li>
        </ul>
        <sub>Virtualisation and infrastructure testing</sub>
      </td>
      <td valign="top">
        <strong>Original Linux Server</strong>
        <ul>
          <li>Lubuntu</li>
          <li>Docker and Docker Compose</li>
          <li>Portainer</li>
          <li>Self-hosted applications</li>
        </ul>
        <sub>Headless server managed remotely</sub>
      </td>
    </tr>
  </tbody>
</table>

⸻

🗺️ Homelab Architecture

The homelab consists of two physical machines: a Dell OptiPlex for virtualisation and an Acer Aspire running Linux and containerised services.

flowchart TB
    H["🖥️ HOMELAB"]
    H --> D["Dell OptiPlex"]
    H --> A["Acer Aspire"]
    D --> P["Proxmox VE"]
    A --> L["Lubuntu"]
    P --> U["🐧 Ubuntu Server VM"]
    P --> W["🪟 Windows Server VM"]
    P --> W11["💻 Windows 11 VM"]
    L --> DC["Docker & Docker Compose"]
    DC --> APPS["Self-Hosted Applications"]
    classDef hardware fill:#dbeafe,stroke:#2563eb,color:#1e3a8a
    classDef platform fill:#dcfce7,stroke:#16a34a,color:#166534
    classDef workload fill:#f3f4f6,stroke:#9ca3af,color:#111827
    classDef containers fill:#fef3c7,stroke:#d97706,color:#92400e
    class D,A hardware
    class P,L platform
    class U,W,W11 workload
    class DC,APPS containers

⸻

🖥️ Dell OptiPlex

Main Virtualisation Server

The Dell OptiPlex is the main virtualisation machine in my homelab.

Running Proxmox VE allows me to host multiple operating systems on one physical machine. Each virtual machine provides a separate environment for administration, testing and troubleshooting.

Virtual Machines

Virtual Machine	Purpose
🐧 Ubuntu Server	Linux administration, server management and infrastructure practice
🪟 Windows Server	Windows server administration and infrastructure testing
💻 Windows 11	Client operating system testing and troubleshooting

What I’m Learning

* Managing virtual machines with Proxmox VE.
* Administering Linux and Windows environments.
* Troubleshooting operating system and networking issues.
* Building and maintaining separate test environments.

Technologies: Proxmox VE · Ubuntu Server · Windows Server · Windows 11

⸻

💻 Acer Aspire

The Original Homelab

An old laptop, a few hardware upgrades and a Linux installation turned the Acer Aspire into a headless server.

I manage it remotely using SSH and use Tailscale for connectivity between devices.

Hardware Specifications

Component	Specification
Model	Acer Aspire ES1-531-C8DA
Processor	Intel Celeron N3050
Memory	8GB RAM
Storage	Kingston 240GB SSD
Operating System	Lubuntu

🐳 Docker & Self-Hosted Applications

Docker and Docker Compose let me deploy and manage applications as containers.

Application	Purpose
Portainer	Managing Docker containers through a web interface
Uptime Kuma	Monitoring service availability
Immich	Self-hosted photo and video management
Nextcloud	Personal cloud and file synchronisation
Navidrome	Self-hosted music streaming
EmulatorJS	Browser-based game emulation

Supporting tools: Docker · Docker Compose · SSH · Tailscale

⸻

💾 Storage & Media

Storage

4TB Seagate IronWolf HDD

Additional storage for the homelab, with NFS used for network file sharing.

Component	Details
Drive	Seagate IronWolf
Capacity	4TB
Network Sharing	NFS
Mount Point	/mnt/storage

🎬 Media Servers

Service	Purpose
Plex	Organising and streaming personal media
Jellyfin	Open-source media management and streaming

These services provide opportunities to practise storage management, filesystem mounts, network shares and media streaming.

⸻

🧰 Technology Stack

A quick overview of the technologies used across the homelab.

Category	Technologies
Virtualisation	Proxmox VE
Operating Systems	Ubuntu Server, Lubuntu, Windows Server, Windows 11
Containers	Docker, Docker Compose, Portainer
Networking	Tailscale, SSH, NFS
Storage	Seagate IronWolf 4TB HDD, network file sharing
Monitoring	Uptime Kuma
Media	Plex, Jellyfin, Navidrome
Self-Hosting	Immich, Nextcloud, EmulatorJS
Hardware	RAM and SSD upgrades, hardware troubleshooting

⸻

🔧 What’s Next?

The homelab is a work in progress. Here’s what I’m planning to explore next:

* Expand the Windows Server lab.
* Practise Linux administration and automation.
* Improve backup and recovery procedures.
* Explore virtual networking and storage.
* Improve service monitoring and reliability.
* Document troubleshooting scenarios.
* Experiment with infrastructure automation.

⸻

📚 Documentation

This repository documents my hardware, infrastructure, services and lessons learned along the way.

As the homelab grows, I’ll add configuration examples, troubleshooting notes and practical guides.

⸻

<div align="center">

Built at home. Learned by doing. Always a work in progress. 🛠️

</div>
