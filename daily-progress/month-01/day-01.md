# Day 1 — Networking Foundations

**Date:** September 16, 2026  
**Roadmap:** Network + Infrastructure + CloudOps Engineering  
**Focus:** Networking Fundamentals

---

## 1. Topics Studied

Completed Jeremy's IT Lab — CCNA Day 1: Network Devices.

Topics covered:

- What is a computer network?
- Client
- Server
- Layer-2 switch
- Router
- Firewall
- Basic network communication

---

## 2. My Understanding

### Computer Network

A computer network is a group of devices that can communicate with each other and exchange information.

### Client

A client is a device that requests or receives information/services from another device.

### Server

A server is a device that provides services or resources to clients.

### Layer-2 Switch

A Layer-2 switch connects multiple devices within a local network (LAN) and forwards Ethernet frames between them.

### Router

A router connects different networks and forwards traffic between those networks.

### Firewall

A firewall controls and filters network traffic according to defined security rules.

---

## 3. Basic Network Flow

The basic communication path I learned:

```text
PC / Client
     |
   Switch
     |
   Router
     |
  Internet
```

---

## 4. Packet Tracer Practice

### Environment

- Cisco Packet Tracer

### Topology

Built a basic topology containing:

- 2 PCs
- 1 Server
- 1 Cisco 2960 Switch
- 1 Router

```text
PC1 ──────┐
          │
PC2 ─── Switch ─── Router
          │
Server ───┘
```

### Objective

Understand how endpoints, switches and routers fit together in a basic network.

### Practice Completed

- Identified PCs
- Identified the server
- Identified the switch
- Identified the router
- Connected the devices
- Observed the physical connections
- Practiced basic network connectivity

### Evidence

![Day 1 Basic Network](day-01-basic-network.png)

---

## 5. Troubleshooting Exercise

I intentionally disconnected the cable between PC1 and the switch.

### Problem

PC1 became disconnected from the network.

### Symptom

The physical link was unavailable.

### Cause

The cable between PC1 and the switch was removed.

### Fix

Reconnected the correct cable.

### Validation

The physical link was restored.

### Lesson Learned

A physical connection problem can cause loss of network connectivity. I practiced checking the physical connection and identifying the affected device before moving to more complex troubleshooting.

---

## 6. Active Recall

After studying the lesson, I closed my notes and practiced explaining the main concepts from memory.

### Basic Network Flow

```text
PC → Switch → Router → Internet
```

---

## 8. What I Learned

- Basic computer networking concepts
- Difference between a client and a server
- Purpose of a Layer-2 switch
- Purpose of a router
- Basic role of a firewall
- How network devices fit together
- Basic physical connectivity troubleshooting
- Importance of observing symptoms before troubleshooting
- How to validate that a problem has been resolved

---

## 9. Day 1 Completion

### Completed

- [x] Jeremy's IT Lab — Day 1: Network Devices
- [x] Networking fundamentals
- [x] Client and server concepts
- [x] Switch, router and firewall concepts
- [x] Packet Tracer practice
- [x] Basic network topology
- [x] Packet Tracer screenshot evidence
- [x] Break/fix troubleshooting exercise
- [x] Active recall
- [x] Closed-book review

### Status

**Day 1 — Completed**

---

## 10. Key Takeaway

The basic network model I learned today:

```text
PC / Client
     |
   Switch
     |
   Router
     |
  Internet
