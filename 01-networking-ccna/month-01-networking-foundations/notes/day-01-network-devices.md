# Day 1 — Network Devices

## Topics Covered

- Computer networks
- Clients
- Servers
- Layer-2 switches
- Routers
- Firewalls
- IP addresses
- Network interfaces/ports

## Key Concepts

### Computer Network
A group of devices connected together so they can communicate.

### Client
A device that requests information or services from a server.

### Server
A device that provides information or services to clients through a network.

### Layer-2 Switch
Connects devices within a network.

### Router
Connects different networks and forwards data between them.

### IP Address
An address used to identify a device on a network.

## Packet Tracer

Built a basic network topology using:

- PC1
- PC2
- Server
- Cisco 2960-24TT Switch
- Router

## Switch Connections

- PC1 → Fa0/1
- PC2 → Fa0/2
- Server → Fa0/3
- Router → Fa0/4

## IP Configuration

### PC1
- IP Address: 192.168.1.10
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.1.1

### PC2
- IP Address: 192.168.1.20
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.1.1

## Cisco IOS Commands Practiced

- show interfaces status
- show vlan brief
- show mac address-table
- show mac address-table dynamic
- show interfaces fa0/1
- show port-security interface fa0/1
- show running-config

## Troubleshooting

Removed the PC1-to-Switch1 cable to simulate a physical connectivity problem.

Reconnected the cable and verified that the physical link was restored.

## Lessons Learned

- Network devices have different roles.
- A switch connects devices within a network.
- A router connects different networks.
- Network devices use interfaces/ports for connections.
- Physical connectivity should be checked when troubleshooting.

- ## Active Recall

### Network Path

PC → Switch → Router → Internet

- PC: End device that requests or uses network services.
- Switch: Connects devices within the same LAN.
- Router: Connects different networks and forwards traffic between them.
- Internet: A global network of interconnected networks.

### Day 1 Flashcards

Reviewed Jeremy's Day 1 flashcards using active recall.

### Self-Assessment

I can explain the basic roles of:
- Network
- Client
- Server
- Switch
- Router
- Firewall
