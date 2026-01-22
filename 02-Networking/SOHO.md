
 # SOHO Networking Cheat Sheet
Small Office / Home Office — Quick Reference

------------------------------------------------------------
## 1. Core SOHO Components
------------------------------------------------------------
Router / Gateway
- Connects LAN ↔ Internet
- Provides DHCP, NAT, Firewall, Port Forwarding
- Often includes built-in Wi-Fi

Switch
- Expands wired ports
- Unmanaged switches common in SOHO
- Used for PCs, printers, NAS, VoIP

Wireless Access Point (WAP)
- May be integrated into router
- Controls SSID, channels, security
- Supports 2.4 GHz / 5 GHz / 6 GHz

Endpoints
- Laptops, desktops, phones
- IoT devices (cameras, thermostats)
- Printers, NAS, smart devices

------------------------------------------------------------
## 2. Wi-Fi Bands Overview
------------------------------------------------------------
2.4 GHz
- Long range
- Slow speed
- High interference
- Best for IoT and long distance

5 GHz
- Medium range
- Fast speed
- Less interference

6 GHz (Wi-Fi 6E/7)
- Shortest range
- Fastest speed
- Very low interference
- Requires modern devices

------------------------------------------------------------
## 3. Security Essentials
------------------------------------------------------------
- Use WPA3 (or WPA2 if needed)
- Disable WPS
- Change default router credentials
- Enable firewall
- Update firmware regularly
- Use Guest Network for visitors
- Strong Wi-Fi passphrase (12+ characters)

------------------------------------------------------------
## 4. IP Addressing Basics
------------------------------------------------------------
DHCP
- Automatically assigns IPs
- Typical SOHO range: 192.168.x.x
- APIPA (169.254.x.x) = DHCP failure

Static IPs (use for:)
- Printers
- NAS
- Servers
- Cameras

------------------------------------------------------------
## 5. Common SOHO Troubleshooting
------------------------------------------------------------
No Internet
- Check modem → router → device
- Restart modem/router
- Verify WAN connection
- Check ISP outage

Wi-Fi Issues
- Change channel to avoid interference
- Move router to central location
- Reduce obstacles (walls, appliances)
- Update wireless drivers

Slow Speeds
- Check ISP bandwidth
- Look for bandwidth-heavy devices
- Use wired for critical systems
- Disable old 802.11b compatibility mode

IP Conflicts
- Ensure DHCP is enabled
- Assign static IPs outside DHCP pool

------------------------------------------------------------
## 6. SOHO Network Layout Example
------------------------------------------------------------
[ISP Modem] → [SOHO Router]
                    ├── LAN Port → Desktop
                    ├── LAN Port → Printer
                    ├── LAN Port → Switch → More Devices
                    └── Wi-Fi → Phones / Laptops / IoT

------------------------------------------------------------
## 7. Useful Router Settings
------------------------------------------------------------
SSID Naming
- Office-WiFi, Office-Guest

Channel Width
- 2.4 GHz → 20 MHz
- 5/6 GHz → 40/80/160 MHz

QoS
- Prioritize VoIP and video calls

Port Forwarding
- For remote access services

UPnP
- Disable unless required

------------------------------------------------------------
## 8. Best Practices
------------------------------------------------------------
- Use wired connections for stability
- Separate guest network from internal LAN
- Document network layout and passwords
- Backup router configuration
- Replace outdated routers (5+ years old)
