# Kubernetes Homelab

## Overview

Project status: **WIP**

This project is to assist in learning Kubernetes and self-hosting applications. The overall goal is to assist in obtaining my CKA (Certified Kuberenetes Administrator).


## Hardware
- 3 × Thinkcentre M900:
    - CPU: `Intel Core i5-6500T @ 2.50GHz`
    - RAM: `16GB`
    - SSD: `128GB`
- 1 x Generic PC Build
    - CPU: `Intel Core i7-6700K @ 4.0GHz`
    - RAM: `32GB`
    - GPU: `Nvidia 1080ti`
    - Storage: `512GB SSD, 256GB SSD, RAID 1 2TB HDD`
- TP-Link `TL-SG105` switch:
    - Ports: `5`
    - Speed: `1000Mbps`

![Homelab](https://i.imgur.com/GehCdqv.jpg)

## Installation / Setup

### Operating System
Lenovo M900s are running Debain 11 "Bullseye", I used a network installation image for each device. The generic PC is running Proxmox 7 with a Ubuntu Server VM.
- [x] Debian (tested on version 11)
- [x] Ubuntu (tested on version 22.04)

Before moving forward

`sudo apt update`

`sudo apt upgrade`

### Automation
Install Ansible v2.4.0+

`sudo apt install ansible`

`git clone https://github.com/dkoke/kubernetes-homelab`
