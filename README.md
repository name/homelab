# My Homelab Infrastructure

> Compute, Networking, and Storage infrastructure at home.

This repository documents my homelab setup, focusing on Compute, Networking, and Storage infrastructure, with an eventual emphasis on Machine Learning applications. The primary goal is to create a robust, scalable, and educational environment for experimenting with various technologies.

## Table of Contents

-   [Overview](#overview)
-   [Naming Scheme](#naming-scheme)
-   [Devices](#devices)
-   [Storage](#storage)
-   [DNS Configuration](#dns-configuration)
-   [Future Plans](#future-plans)
-   [Setup and Configuration](#setup-and-configuration)

## Overview

This homelab is designed to provide a comprehensive learning and testing environment for various IT and data science technologies. The infrastructure is built with a focus on:

-   Scalability
-   Reliability
-   Security
-   Performance

## Naming Scheme

-   `rtr`: Router
-   `swc`: Core Switch
-   `swa`: Access Switch
-   `nas`: Network Attached Storage

## Devices

| Device                   | Model                                           | IP Address    | Hostname      |
| ------------------------ | ----------------------------------------------- | ------------- | ------------- |
| Edge Router/Firewall     | Juniper SRX300 (CHASSIS PAIR)                   | 192.168.1.1   | hl-ldn-rtr-1  |
| Core Switch              | NETGEAR ProSafe 24 Port GS724T                  | 192.168.1.110 | hl-ldn-swc-1  |
| Access Switch            | Juniper EX2200-C                                | 192.168.1.120 | hl-ldn-swa-1  |
| Network Attached Storage | ReadyNAS 4 TB                                   | 192.168.1.150 | hl-ldn-nas-1  |
| Operations PC            | AMD Ryzen 7 7800X3D, 64 GB RAM, NVIDIA RTX 4060 | 192.168.1.222 | hl-ldn-pc-ops |
| Macbook Air M2           | Apple M2, 16 GB RAM, 1 TB SSD                   | DHCP          | hl-ldn-mac-1  |
| Raspberry Pi 4           | Raspberry Pi 4, 8 GB RAM, 1 TB SSD              | 192.168.231   | hl-ldn-node-1 |
| Raspberry Pi 4           | Raspberry Pi 4, 8 GB RAM, 1 TB SSD              | 192.168.232   | hl-ldn-node-2 |
| Raspberry Pi 4           | Raspberry Pi 4, 8 GB RAM, 1 TB SSD              | 192.168.233   | hl-ldn-node-3 |

## Storage

### Network Shares:

-   hl-ldn-data: General data
-   hl-ldn-media: Video and audio
-   hl-ldn-backup: System backups

## DNS Configuration

DNS servers used in the homelab:

-   1.1.1.2
-   1.0.0.2

## Future Plans

1. Implement ML-specific infrastructure
2. Expand storage capacity

## Setup and Configuration

-   TODO
