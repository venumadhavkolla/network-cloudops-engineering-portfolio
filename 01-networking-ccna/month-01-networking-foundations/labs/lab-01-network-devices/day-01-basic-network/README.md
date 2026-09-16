# Day 1 — Basic Network Topology

## Objective

Build a basic network topology in Cisco Packet Tracer and understand the roles of network devices.

## Devices

- PC1
- PC2
- Server
- Cisco 2960-24TT Switch
- Router

## Topology

PC1 ──┐
PC2 ──┤
Server ┤── Switch1 ── Router1
       ┘

## Connections

| Device | Device Interface | Switch Port |
|---|---|---|
| PC1 | FastEthernet0 | Fa0/1 |
| PC2 | FastEthernet0 | Fa0/2 |
| Server | FastEthernet0 | Fa0/3 |
| Router | — | Fa0/4 |

## IP Configuration

| Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| PC1 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| PC2 | 192.168.1.20 | 255.255.255.0 | 192.168.1.1 |

## Switch Configuration

- Fa0/1 → VLAN 1
- Fa0/2 → VLAN 1
- Fa0/3 → VLAN 1
- Fa0/4 → VLAN 1
- Port status verified as On/connected

## Commands Practiced

```text
show interfaces status
show vlan brief
show mac address-table
show mac address-table dynamic
show interfaces fa0/1
show port-security interface fa0/1
show running-config
