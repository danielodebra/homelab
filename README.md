<div align="center">

# 🖥️ My Homelab

Linux • Virtualisation • Self-Hosting • Infrastructure

A small collection of hardware, virtual machines and self-hosted services that I’m building, maintaining and experimenting with at home.

</div>

⸻

## 👋 About the Project

My homelab started with an old Acer Aspire laptop that I brought back to life and turned into a Linux server.

Since then, I’ve added a Dell OptiPlex running Proxmox VE, Windows and Linux virtual machines, dedicated storage, and a collection of self-hosted applications.

I use it to experiment with technology, troubleshoot problems and learn by building things myself.

The idea is simple: build it, run it, break it, fix it, and learn something along the way.

⸻

## 🏗️ Infrastructure at a Glance

<table>
<tr>
<td width="50%" valign="top">

🖥️ Dell OptiPlex

Main virtualisation server

* ⚙️ Proxmox VE
* 🐧 Ubuntu Server VM
* 🪟 Windows Server VM
* 💻 Windows 11 VM

Used for virtualisation, operating system administration and infrastructure testing.

</td>
<td width="50%" valign="top">

💻 Acer Aspire

Original Linux server

* 🐧 Lubuntu
* 🐳 Docker & Docker Compose
* 📦 Portainer
* 🏠 Self-hosted applications

Repurposed laptop running headlessly, managed remotely over SSH.

</td>
</tr>
</table>


⸻

## 🖥️ 01 — Dell OptiPlex

The virtualisation box

Proxmox VE is the foundation of my main server. It lets me run separate operating systems on the same physical machine and experiment without needing dedicated hardware for each environment.

Virtual machine	Purpose
🐧 Ubuntu Server	Linux administration, server services and storage
🪟 Windows Server	Windows infrastructure and server administration practice
💻 Windows 11	Client OS testing and troubleshooting

Things I’m working with

Proxmox VE · Linux · Windows Server · Virtual Machines · Networking

⸻

## 💻 02 — Acer Aspire

The original homelab

An old laptop, a few hardware upgrades and a Linux installation turned this machine into a headless server.

I manage it remotely using SSH and use Tailscale for connectivity between devices.

Component	Specification
Model	Acer Aspire ES1-531-C8DA
CPU	Intel Celeron N3050
Memory	8GB RAM
Storage	Kingston 240GB SSD
Operating system	Lubuntu

🐳 Docker & Self-Hosted Applications

A selection of applications in my environment:

Application	What it does
Portainer	Docker container management
Uptime Kuma	Service uptime monitoring
Immich	Photo and video management
Nextcloud	Personal cloud and file synchronisation
Navidrome	Self-hosted music streaming
EmulatorJS	Browser-based game emulation

Under the hood: Docker, Docker Compose, SSH and Tailscale.

⸻

## 💾 03 — Storage & Media

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

## 🧰 The Toolkit

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

## 🔧 What’s Next?

The homelab is always evolving. Here’s what’s on my radar:

* Expand my Windows Server lab.
* Practise Linux administration and automation.
* Improve backup and recovery procedures.
* Explore virtual networking and storage.
* Improve service monitoring and reliability.
* Document more troubleshooting scenarios.
* Experiment with infrastructure automation.

⸻

## 📚 Documentation

This repository is where I document the setup, the services I run, and the things I learn along the way.

As the homelab grows, I’ll add more configuration examples, troubleshooting notes and practical documentation.

<div align="center">

Built at home. Learned by doing. Always a work in progress. 🛠️

</div>
