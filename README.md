 <div align="center">

# 🖥️ My Homelab

**Linux · Virtualisation · Self-Hosting · Infrastructure**

A personal homelab built around Proxmox VE and a repurposed Linux server, providing hands-on experience with virtualisation, Linux and Windows administration, Docker, networking and self-hosted applications.

</div>


## 👋 About the Project

My homelab started with an old Acer Aspire laptop that I brought back to life and turned into a Linux server.

Since then, I’ve added a Dell OptiPlex running Proxmox VE, Windows and Linux virtual machines, additional storage, and a collection of self-hosted applications.

I use it to experiment with technology, troubleshoot problems and learn by building things myself.

The idea is simple: Build it, run it, break it, fix it, and learn something along the way.



## 🏗️ Infrastructure at a Glance

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🖥️ Dell OptiPlex</h3>
      <p><strong>Main virtualisation server</strong></p>
      <ul>
        <li>⚙️ Proxmox VE</li>
        <li>🐧 Ubuntu Server VM</li>
        <li>🪟 Windows Server VM</li>
        <li>💻 Windows 11 VM</li>
      </ul>
      <p><em>Virtualisation and infrastructure testing.</em></p>
    </td>
    <td width="50%" valign="top">
      <h3>💻 Acer Aspire</h3>
      <p><strong>Original Linux server</strong></p>
      <ul>
        <li>🐧 Lubuntu</li>
        <li>🐳 Docker &amp; Docker Compose</li>
        <li>📦 Portainer</li>
        <li>🏠 Self-hosted applications</li>
      </ul>
      <p><em>Headless server managed remotely.</em></p>
    </td>
  </tr>
</table>

 
 


## 🖥️ Dell OptiPlex

**Role:** Main virtualisation server

The Dell OptiPlex is the main virtualisation machine in my homelab.

Running Proxmox VE allows me to host multiple operating systems on one physical machine, providing separate environments for administration, testing and troubleshooting.

### Virtual Machines

| Virtual Machine | Purpose |
|---|---|
| Ubuntu Server | Linux administration, server services and infrastructure practice |
| Windows Server | Windows infrastructure and server administration |
| Windows 11 | Client operating system testing and troubleshooting |

**Technologies:** Proxmox VE · Linux · Windows Server · Virtualisation · Networking


## 💻 Acer Aspire

**Role:** Headless Linux server

An old laptop, a few hardware upgrades and a Linux installation turned the Acer Aspire into a headless server.

I manage it remotely using SSH and use Tailscale to connect to devices across my setup.

### Hardware & Operating System

| Component | Specification |
|---|---|
| Model | Acer Aspire ES1-531-C8DA |
| CPU | Intel Celeron N3050 |
| Memory | 8GB RAM |
| Storage | Kingston 240GB SSD |
| Operating system | Lubuntu |
| Remote access | SSH and Tailscale |

### 🐳 Docker & Self-Hosted Applications

Docker and Docker Compose provide a way to run and manage applications as containers.

| Application | Purpose |
|---|---|
| Portainer | Docker container management |
| Uptime Kuma | Service uptime monitoring |
| Immich | Photo and video management |
| Nextcloud | Personal cloud and file synchronisation |
| Navidrome | Self-hosted music streaming |
| EmulatorJS | Browser-based game emulation |

**Technologies:** Lubuntu · Docker · Docker Compose · SSH · Tailscale
 


 ## 💾 Storage & Media

The homelab uses additional HDD storage for media and other files, with NFS providing network file sharing.

### Storage

| Component | Details |
|---|---|
| Drive | Seagate IronWolf |
| Capacity | 4TB |
| Filesystem | ext4 |
| Mount point | `/mnt/storage` |
| Network sharing | NFS |

### 🎬 Media Servers

| Service | Purpose |
|---|---|
| Plex | Organising and streaming personal media |
| Jellyfin | Open-source media management and streaming |

This part of the setup provides practical experience with Linux filesystems, storage mounts, network shares and self-hosted media services. 



## 🧰 The Toolkit

| Category | Tools & Technologies |
|---|---|
| Virtualisation | Proxmox VE |
| Operating systems | Ubuntu Server, Lubuntu, Windows Server, Windows 11 |
| Containers | Docker, Docker Compose, Portainer |
| Networking | Tailscale, SSH, NFS |
| Storage | Seagate IronWolf 4TB HDD, ext4, NFS |
| Monitoring | Uptime Kuma |
| Media | Plex, Jellyfin, Navidrome |
| Self-hosting | Immich, Nextcloud, EmulatorJS |
| Hardware | RAM and SSD upgrades, hardware troubleshooting |




## 🔧 What's Next?

The homelab is always evolving. Here are some areas I'm looking to work on next:

- [ ] Expand my Windows Server lab.
- [ ] Practise Linux administration and automation.
- [ ] Improve backup and recovery procedures.
- [ ] Explore virtual networking and storage.
- [ ] Improve service monitoring and reliability.
- [ ] Document troubleshooting scenarios.
- [ ] Experiment with infrastructure automation.



## 📚 Documentation

This repository documents my homelab infrastructure, self-hosted applications and the lessons learned while maintaining the setup.

Planned documentation includes:

- Architecture and infrastructure overview.
- Hardware specifications.
- Storage and NFS configuration.
- Troubleshooting and recovery procedures.



<div align="center">

 
</div>
