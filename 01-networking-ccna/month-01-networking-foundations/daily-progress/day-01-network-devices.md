# Day 1 — Network Devices

## Status

✅ Completed

## Learning

Completed Jeremy's IT Lab Day 1 lesson.

Covered:

- Computer networks
- Client and server
- Layer-2 switches
- Routers
- Firewalls
- IP addresses
- Network interfaces

## Packet Tracer Lab

Built a basic network topology using:

- PC1
- PC2
- Server1
- Cisco 2960-24TT Switch1
- Router1

### Connections

- PC1 → Switch1 Fa0/1
- PC2 → Switch1 Fa0/2
- Server1 → Switch1 Fa0/3
- Router1 → Switch1 Fa0/4

### IP Addressing

PC1:

- IP: 192.168.1.10
- Mask: 255.255.255.0
- Gateway: 192.168.1.1

PC2:

- IP: 192.168.1.20
- Mask: 255.255.255.0
- Gateway: 192.168.1.1

## Commands Practiced

```text
show interfaces status
show vlan brief
show mac address-table
show mac address-table dynamic
show interfaces fa0/1
show port-security interface fa0/1
show running-config
