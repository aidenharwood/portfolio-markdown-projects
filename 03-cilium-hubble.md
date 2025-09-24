---
title: Cilium CNI with Hubble UI
---
title: Cilium CNI with Hubble UI
description: High-performance Kubernetes networking with Cilium CNI and observability through Hubble's intuitive web interface for traffic monitoring and security insights.
date: 2024-01-15
tags: [cilium, cni, kubernetes, networking, observability, ebpf]
image: /images/projects/hubble.png
demo: https://hubble.aidenharwood.uk
status: completed
---

## Overview

Cilium is a cloud-native networking solution that provides high-performance networking, load balancing, and security for Kubernetes clusters using eBPF technology. Hubble is Cilium's observability layer that provides deep network visibility and monitoring capabilities through an intuitive web interface.

## Features

- **eBPF-based Networking**: High-performance packet processing in the kernel
- **Network Policies**: Advanced security with Layer 3/4 and Layer 7 policies
- **Service Mesh**: Built-in service mesh capabilities without sidecars
- **Observability**: Real-time network flow monitoring with Hubble UI
- **Load Balancing**: Efficient traffic distribution and routing

## Technical Details

Cilium leverages eBPF (extended Berkeley Packet Filter) to provide efficient networking and security enforcement directly in the Linux kernel. Hubble acts as the observability layer, capturing and analyzing network flows to provide insights into service dependencies, traffic patterns, and security events through its web-based dashboard.