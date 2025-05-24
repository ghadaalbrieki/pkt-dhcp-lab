# 🌐 DHCP Network Simulation Lab

This is a simple network simulation project using **Cisco Packet Tracer**. The goal is to configure DHCP and enable routing between two separate networks.

---

## 🖥️ Network Components

- 2 Routers (Router0, Router1)
- 2 Switches
- 4 PCs (A1, A2, B1, B2)
- 1 DHCP Server

---

## 🗺️ IP Addressing and Subnets

| Subnet         | Devices                  | DHCP Source     |
|----------------|---------------------------|------------------|
| 192.168.1.0/24 | A1, A2                    | Router0 (DHCP)   |
| 192.168.2.0/24 | B1, B2, DHCP Server       | Server0 (DHCP)   |
| 192.168.3.0/24 | Router0 <--> Router1 Link | Static IPs       |

---

## ⚙️ Configuration Summary

- **Router0** provides DHCP to the 192.168.1.0/24 subnet.
- **Server0** provides DHCP to the 192.168.2.0/24 subnet.
- Routers are connected via a third subnet using static IPs.
- All PCs are set to obtain IP addresses automatically.

---

## ✅ Connectivity Test

- A1 successfully pinged B1.
- B2 successfully pinged A2.
- This confirms that DHCP and inter-network routing are working correctly.

---

 📸 Screenshot

Please find the network topology screenshot saved as 'screenshot.png' in this folder.


---

## 📁 Files Included

| File Name          | Description                        |
|--------------------|------------------------------------|
| `README.md`        | This documentation file            |
| `DHCP-Lab.pkt`     | Cisco Packet Tracer project file   |
| `screenshot.png`   | Screenshot of the network topology |

---

## 🔧 Ideas for Future Enhancements

- Add VLANs to segment internal networks.
- Implement NAT to simulate internet access.
- Add ACLs for traffic filtering.
- Set up DNS and web server roles on the DHCP server.
- Include wireless access points.

---

## 👩‍💻 Created by

Ghada Albrieki
