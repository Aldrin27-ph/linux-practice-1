# Day 6–7: Networking Fundamentals (Cloud Foundation)

## Overview
Today I studied core networking concepts that are foundational for cloud computing. This includes how data moves across networks, how devices communicate, and how Ethernet and TCP/IP models work. These concepts are critical because **cloud infrastructure relies heavily on networking**.

> “If the network goes down, the business will stop.”

---

## Core Networking Concepts

### Router
A **router** is a device that knows how to forward data between independent networks. It operates at **Layer 3 (Network Layer)** of the TCP/IP model.

---

## TCP/IP Five-Layer Model

### 1. Physical Layer
- Represents the physical devices that interconnect computers.
- Examples: cables, hubs.
- **Hub**: A physical-layer device that allows many computers to connect at once.
- **Collision Domain**: A network segment where only one device can communicate at a time. If multiple systems transmit simultaneously, electrical pulses can interfere.

---

### 2. Data Link / Network Access Layer
- Defines how signals are interpreted so devices can communicate.
- Responsible for communication on the **same network**.
- Examples:
  - Ethernet
  - Wi-Fi
  - Switches

---

### 3. Network / Internet Layer
- Allows **different networks** to communicate.
- Uses **routers**.
- **Internetwork**: A collection of networks connected by routers (e.g., the Internet).
- **IP (Internet Protocol)**: Core protocol that enables global communication.

---

### 4. Transport Layer
- Determines which client and server applications receive data.
- Uses:
  - **TCP** (reliable)
  - **UDP** (faster, connectionless)
- Uses **ports**.

---

### 5. Application Layer
- User-facing protocols.
- Examples:
  - HTTP
  - SMTP
  - FTP

---

## Routing and Internet Protocols

### Border Gateway Protocol (BGP)
- Routers share routing information using BGP.
- Enables routers to learn the most optimal paths for traffic across the Internet.

---

## Practice Assignment Definitions

- **Switch**: Connects many devices and inspects Ethernet frames.
- **LAN (Local Area Network)**: A network covering a small geographic area.
- **Router**: Connects independent networks and forwards data.
- **Server**: A system that provides data or services to clients.
- **Copper Cables**: Use voltage changes to transmit data.

---

## Data Transmission Basics

### Bit
- The smallest unit of data: **1 or 0**.

### Modulation
- Varying voltage levels to represent data over a cable.

### Twisted Pair Cable
- Most common cabling type.
- Uses twisted copper wire pairs to reduce interference.

---

## Communication Types

- **Simplex**: One-directional communication.
- **Duplex**: Communication flows in both directions.

---

## Ethernet Fundamentals

### RJ45 Ports
- **Link LED**: Indicates a proper cable connection.
- **Activity LED**: Flashes when data is transmitted.

### Ethernet
- Most widely used protocol for local network communication.
- Uses **CSMA/CD (Carrier Sense Multiple Access with Collision Detection)** to manage transmission timing.

---

## MAC Addressing

### MAC Address
- A globally unique 48-bit identifier.
- Represented as six hexadecimal octets (e.g., `AA:BB:CC:DD:EE:FF`).

### Hexadecimal
- Base-16 numbering system (0–9, A–F).

### Octet
- 8 bits of data.

### Organizationally Unique Identifier (OUI)
- First three octets of a MAC address.
- Identifies the manufacturer.

---

## Ethernet Addressing Types

- **Unicast**: One-to-one communication.
- **Multicast**: One-to-many communication.
- **Broadcast**: One-to-all communication.
  - Broadcast MAC address: `FF:FF:FF:FF:FF:FF`

---

## Ethernet Frame Structure

- **Preamble (7 bytes)**: Synchronizes sender and receiver.
- **Start Frame Delimiter (1 byte)**: Signals start of the frame.
- **Destination MAC Address (6 bytes)**
- **Source MAC Address (6 bytes)**
- **EtherType (2 bytes)**: Indicates protocol type.
- **VLAN Header (optional, 4 bytes)**: Identifies VLAN frames.
- **Payload**: Actual transmitted data.
- **Frame Check Sequence (FCS, 4 bytes)**:
  - Uses **Cyclical Redundancy Check (CRC)**
  - Ensures data integrity.

---

## Key Definitions Review

1. A MAC address consists of **6 octets (48 bits)**.
2. Ethernet broadcast address: `FF:FF:FF:FF:FF:FF`.
3. **CRC** ensures no data corruption occurred.
4. **Broadcast**: One device sends data to all devices.
5. **Multicast**: One device sends data to multiple devices.
6. **Unicast**: One device sends data to one device.
7. **Preamble**: First part of an Ethernet frame.
8. **Payload**: Data from higher layers being transmitted.

---

## Knowledge Check (True / Definitions)

1. TCP ensures reliable data delivery — **True**
2. Application layer is the fifth layer of TCP/IP — **True**
3. Data Link layer abstracts hardware differences — **True**
4. Fiber cables transmit data using pulses of light.
5. Routers operate at **Layer 3** of the TCP/IP model.
6. Clients request data from servers.
7. Duplex allows two-way data flow.
8. Port lights help with troubleshooting.

---

## Reflection
Networking is a critical foundation of cloud computing. Understanding how data flows, how devices communicate, and how Ethernet and TCP/IP operate will help me troubleshoot cloud infrastructure, configure networks, and support real-world systems effectively.
