
# 📝 Day 1: Networking Basics – Routers, Switches, Hubs & Data Transmission Modes

## 📡 What is Networking?
Networking refers to the **interconnection of computers and devices** to share data and resources. It enables communication between systems using networking devices and protocols.

---

## 🔌 Network Devices:

### 1. **Router**
- 🧠 *Smart* device that **connects multiple networks** (e.g., LAN to WAN).
- Works at **Layer 3 (Network Layer)** of the OSI model.
- Can perform **routing** based on IP addresses.
- Provides **default gateway** to hosts for external communication.

**Example:** Connects your home LAN to the internet.

---

### 2. **Switch**
- 🧠 *Semi-smart* device that connects multiple devices within the **same network (LAN)**.
- Works at **Layer 2 (Data Link Layer)**.
- Uses **MAC addresses** to forward data to the correct port.
- Reduces collisions and improves network efficiency.

**Example:** Used in office LANs to connect computers, printers, etc.

---

### 3. **Hub**
- 🧱 *Dumb* device that broadcasts data to **all connected devices**.
- Works at **Layer 1 (Physical Layer)**.
- Has **no intelligence**, does not filter or direct traffic.
- Causes **network congestion and collisions**.

**Example:** Very outdated, mostly replaced by switches.

---

## 🛰️ Types of Data Transmission:

### ✅ **Unicasting**
- Data is sent from **one source to one destination**.
- Most common communication method (e.g., downloading a file).

### ✅ **Broadcasting**
- Data is sent from **one source to all devices** in the network.
- Used in hubs and older switches.
- Can cause congestion in large networks.

### ✅ **Multicasting**
- Data is sent from **one source to a selected group** of devices.
- Efficient for group communication like video conferencing or IPTV.
- Requires support from routers/switches.

---

## 🧠 Summary Table:

| Device   | OSI Layer | Intelligence | Targeted Communication | Use Case                  |
|----------|-----------|--------------|-------------------------|---------------------------|
| Router   | Layer 3   | High         | IP-based (between networks) | Internet connection sharing |
| Switch   | Layer 2   | Medium       | MAC-based (within LAN)  | Office/college networks   |
| Hub      | Layer 1   | Low          | Broadcast to all        | Obsolete                  |

---
