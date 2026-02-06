# Network Emulation with Kathará

## Overview
This project emulates a **multi-router IP network** using **Kathará**, with fully static routing and strict traffic policies between networks.

All configurations are automated via startup scripts, ensuring reproducibility and correctness.

## Network Characteristics
- Multiple hosts and routers
- Static IP addressing
- Static routing policies
- Asymmetric routing paths
- Full connectivity between hosts

## Routing Policies
- Traffic from Network A → B routed via r1 → r2 → r3
- Traffic from Network B → A routed via r3 → r4 → r1
- Default gateways configured on all hosts

## Validation
- Connectivity tests using `ping`
- Routing table inspection
- ICMP traffic analysis with `tcpdump`
- Packet capture and analysis (`.pcap` files)

## Technologies
- Kathará
- Linux networking
- Static routing
- tcpdump

## Skills Demonstrated
- Network design and configuration
- Routing policy enforcement
- Network debugging and analysis
- Emulation and testing

## Academic Context
Computer Networks (TPC3 – 2025/2026)
