# 🖥️ My Homelab — Linux, Virtualisation & Self-Hosted Infrastructure

My homelab started with an old Acer Aspire laptop that I brought back to life and turned into a Linux server. Since then, I’ve expanded it with additional hardware, a Proxmox virtualisation server, Windows and Linux environments, and more self-hosted services.

I use my homelab to experiment with different technologies, get hands-on with infrastructure, and learn by building and troubleshooting things myself. It’s an ongoing project that grows as I introduce new tools, services and ideas.

## 🏗️ Infrastructure Overview

My current setup consists of two main physical machines, each serving a different purpose.

### Machine	Role	Operating System / Platform
### Dell OptiPlex	Main virtualisation server	Proxmox VE
### Acer Aspire ES1-531-C8DA	Original Linux server and self-hosting	Lubuntu

## 🖥️ Dell OptiPlex — Main Proxmox Server

The Dell OptiPlex is the main virtualisation host in my homelab. It runs Proxmox VE, allowing me to manage separate virtual machines for Linux, Windows Server and Windows client environments.

Virtual machines:

VM	Operating System	Purpose
Ubuntu Server	Ubuntu Server	Linux administration, Docker, self-hosted services and storage
Windows Server	Windows Server	Windows infrastructure and server administration practice
Windows 11	Windows 11	Windows client administration, testing and troubleshooting

I’m using this environment to develop my understanding of virtualisation, operating system administration, networking and how different systems work together.

## 💻 Acer Aspire — Original Linux Server

The Acer Aspire was where my homelab journey began. I repurposed the laptop, upgraded its hardware and installed Lubuntu to run as a headless Linux server.

I manage it remotely over SSH and use Tailscale to connect to my homelab services and devices.

Hardware:

Component	Specification
Model	Acer Aspire ES1-531-C8DA
CPU	Intel Celeron N3050
RAM	8GB
Storage	Kingston 240GB SSD
Operating System	Lubuntu

Services and tools:

Technology	Purpose
Docker	Running containerised applications
Docker Compose	Managing multi-container applications
Portainer	Container management
Uptime Kuma	Service availability monitoring
Tailscale	Secure connectivity between devices
Immich	Photo and video management
Nextcloud	Personal cloud storage and file synchronisation
Navidrome	Self-hosted music streaming
EmulatorJS	Browser-based game emulation

This machine remains part of my setup and gives me a practical environment for experimenting with Linux, Docker and self-hosted applications.

## 🧰 Technologies I’m Working With

Virtualisation

* Proxmox VE
* Virtual machine management

Operating Systems & Administration

* Ubuntu Server
* Lubuntu
* Windows Server
* Windows 11
* SSH and Linux command-line administration

Containers & Self-Hosting

* Docker
* Docker Compose
* Portainer
* Immich
* Nextcloud
* Navidrome

Networking & Storage

* Tailscale
* NFS and network file sharing
* Virtual networking
* Remote access and connectivity troubleshooting

Monitoring

* Uptime Kuma
* Service availability monitoring

Hardware

* Hardware troubleshooting
* RAM and SSD upgrades
* Repurposing older hardware

## 🔧 What I’m Exploring Next

My homelab is a work in progress, and there are plenty of things I want to build and improve.

Some of the areas I’m exploring include:

* Expanding my Windows Server lab and learning more about Windows infrastructure.
* Improving my Linux server administration skills.
* Practising backup and recovery procedures.
* Learning more about networking, storage and virtualisation.
* Exploring automation and repeatable infrastructure deployments.
* Improving monitoring and troubleshooting across my services.

## 📚 Documentation

This repository is where I document my homelab setup, the tools I’m using, and the things I learn along the way.

As the environment grows, I’ll continue adding documentation, configuration examples and troubleshooting notes to make it easier to understand how everything fits together.

It’s very much a work in progress, and that’s part of the point.
