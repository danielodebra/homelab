<div align="center">

🖥️ My Homelab

Linux · Virtualisation · Self-Hosting · Infrastructure

A small collection of hardware, virtual machines and self-hosted services that I’m building, maintaining and experimenting with at home.

</div>

⸻

👋 About the Project

My homelab started with an old Acer Aspire laptop that I brought back to life and turned into a Linux server.

Since then, I’ve added a Dell OptiPlex running Proxmox VE, Windows and Linux virtual machines, additional storage, and a collection of self-hosted applications.

I use it to experiment with technology, troubleshoot problems and learn by building things myself.

The idea is simple: Build it, run it, break it, fix it, and learn something along the way.

⸻

🏗️ Infrastructure at a Glance

🖥️ Dell OptiPlex	💻 Acer Aspire
Main virtualisation server	Original Linux server
⚙️ Proxmox VE	🐧 Lubuntu
🐧 Ubuntu Server VM	🐳 Docker & Docker Compose
🪟 Windows Server VM	📦 Portainer
💻 Windows 11 VM	🏠 Self-hosted applications
Virtualisation and infrastructure testing	Headless server managed remotely

⸻

🗺️ How It Fits Together

flowchart TB
    H["🖥️ HOMELAB"]
    H --> D["Dell OptiPlex"]
    H --> A["Acer Aspire"]
    D --> P["Proxmox VE"]
    A --> L["Lubuntu"]
    P --> U["Ubuntu Server"]
    P --> W["Windows Server"]
    P --> W11["Windows 11"]
    L --> DS["Docker Services"]
    DS --> S["Self-Hosted Apps"]

⸻

🖥️ Dell OptiPlex

Main Virtualisation Server

The Dell OptiPlex is the main virtualisation machine in my homelab.

Running Proxmox VE allows me to host multiple operating systems on one physical machine, giving me separate environments to practise administration, test configurations and troubleshoot problems.

Virtual machines

Virtual Machine	Purpose
🐧 Ubuntu Server	Linux administration, server services and infrastructure practice
🪟 Windows Server	Windows infrastructure and server administration
💻 Windows 11	Client operating system testing and troubleshooting

Technologies: Proxmox VE · Linux · Windows Server · Virtual Machines · Networking

⸻

💻 Acer Aspire

The Original Homelab

An old laptop, a few hardware upgrades and a Linux installation turned the Acer Aspire into a headless server.

I manage it remotely using SSH and use Tailscale to connect to devices across my setup.

Hardware and operating system

Component	Specification
Model	Acer Aspire ES1-531-C8DA
CPU	Intel Celeron N3050
Memory	8GB RAM
Storage	Kingston 240GB SSD
Operating system	Lubuntu

🐳 Docker & Self-Hosted Applications

Docker and Docker Compose provide a way to run and manage applications as containers.

Application	Purpose
Portainer	Docker container management
Uptime Kuma	Service uptime monitoring
Immich	Photo and video management
Nextcloud	Personal cloud and file synchronisation
Navidrome	Self-hosted music streaming
EmulatorJS	Browser-based game emulation

Under the hood: Docker · Docker Compose · SSH · Tailscale

⸻

💾 Storage & Media

Storage

4TB Seagate IronWolf HDD

Additional storage for my homelab, with NFS used for network file sharing.

Component	Details
Drive	Seagate IronWolf
Capacity	4TB
Network sharing	NFS
Mount point	/mnt/storage

🎬 Media Servers

Service	Purpose
Plex	Organising and streaming personal media
Jellyfin	Open-source media management and streaming

This part of the setup gives me practical experience with storage, filesystem mounts, network shares and self-hosted media services.

⸻

🧰 The Toolkit

A quick overview of the technologies across my homelab.

Category	Tools & Technologies
Virtualisation	Proxmox VE
Operating systems	Ubuntu Server, Lubuntu, Windows Server, Windows 11
Containers	Docker, Docker Compose, Portainer
Networking	Tailscale, SSH, NFS
Storage	Seagate IronWolf 4TB HDD, network file sharing
Monitoring	Uptime Kuma
Media	Plex, Jellyfin, Navidrome
Self-hosting	Immich, Nextcloud, EmulatorJS
Hardware	RAM and SSD upgrades, hardware troubleshooting

⸻

🔧 What’s Next?

The homelab is always evolving. Here’s what I’m looking to work on next:

* Expand my Windows Server lab.
* Practise Linux administration and automation.
* Improve backup and recovery procedures.
* Explore virtual networking and storage.
* Improve service monitoring and reliability.
* Document troubleshooting scenarios.
* Experiment with infrastructure automation.

⸻

📚 Documentation

This repository is where I document my setup, the services I run and the things I learn along the way.

As the homelab grows, I’ll add more configuration examples, troubleshooting notes and practical documentation.

<div align="center">

Built at home. Learned by doing. Always a work in progress. 🛠️

</div>
