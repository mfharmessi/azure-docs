---
title: Azure PowerShell samples for virtual network
description: Learn about Azure PowerShell samples for managing virtual networks, including a sample for creating a virtual network for multi-tier applications.
services: virtual-network
documentationcenter: virtual-network
author: asudbring
manager: mtillman
ms.service: virtual-network
ms.topic: sample
ms.workload: infrastructure
ms.custom: devx-track-azurepowershell
ms.date: 07/15/2019
ms.author: allensu
---
# Azure PowerShell samples for virtual network

The following table includes links to Azure PowerShell scripts:

| Script | Description |
|----|----|
| [Create a virtual network for multi-tier applications](./scripts/virtual-network-powershell-sample-multi-tier-application.md) | Creates a virtual network with front-end and back-end subnets. Traffic to the front-end subnet is limited to HTTP, while traffic to the back-end subnet is limited to SQL, port 1433. |
| [Peer two virtual networks](./scripts/virtual-network-powershell-sample-peer-two-virtual-networks.md) | Creates and connects two virtual networks in the same region. |
| [Route traffic through a network virtual appliance](./scripts/virtual-network-powershell-sample-route-traffic-through-nva.md) | Creates a virtual network with front-end and back-end subnets and a VM that is able to route traffic between the two subnets. |
| [Filter inbound and outbound VM network traffic](./scripts/virtual-network-powershell-sample-filter-network-traffic.md) | Creates a virtual network with front-end and back-end subnets. Inbound network traffic to the front-end subnet is limited to HTTP and HTTPS. Outbound traffic to the internet from the back-end subnet is not permitted. |
|[Configure IPv4 + IPv6 dual stack virtual network with Basic Load Balancer](./scripts/virtual-network-powershell-sample-ipv6-dual-stack.md)|Deploys dual-stack (IPv4+IPv6) virtual network with two VMs and an Azure Basic Load Balancer with IPv4 and IPv6 public IP addresses. |
|[Configure IPv4 + IPv6 dual stack virtual network with Standard Load Balancer](./scripts/virtual-network-powershell-sample-ipv6-dual-stack-standard-load-balancer.md)|Deploys dual-stack (IPv4+IPv6) virtual network with two VMs and an Azure Standard Load Balancer with IPv4 and IPv6 public IP addresses. |
