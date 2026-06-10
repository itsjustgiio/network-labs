# Wireless Technologies Simulation

## Objective

Configure multiple wireless access methods for office devices using WLAN, Bluetooth, and cellular tethering.

## Description

Configured wireless connectivity for office devices in Cisco Packet Tracer. Connected a laptop to the employee WLAN, paired a tablet with a Bluetooth speaker, and tethered a laptop through a smartphone so it could use the cellular network. Verified that each connection method worked by checking addressing, pairing status, and access to the internal web server.

## Topology

![Wireless technologies topology](tether-access.png)

## Network Components

- Laptop
- User-Laptop
- Smartphone
- Office Tablet
- Bluetooth Speaker
- Office WLAN
- Cellular Network
- Office-Server

## Skills Demonstrated

- Cisco Packet Tracer
- Wireless Networking
- WLAN Configuration
- SSID Authentication
- Bluetooth Pairing
- Cellular Tethering
- DHCP Verification
- Web Connectivity Testing
- Mobile Device Connectivity

## Tasks Performed

- Installed a wireless module in the laptop
- Connected the laptop to the `Employee` wireless network
- Verified the laptop received an IP address
- Paired the Office Tablet with a Bluetooth speaker
- Tested Bluetooth audio using the music player
- Enabled cellular tethering on the smartphone
- Connected User-Laptop to the smartphone over Bluetooth
- Verified web access to `office.srv`

## Verification

The laptop connected to the office WLAN and received network addressing. The tablet successfully paired with the Bluetooth speaker, and the User-Laptop was able to use the smartphone tethering connection to reach `office.srv`.

### Laptop IP Configuration

![Laptop IP configuration](laptop-ipconfig.png)

### Bluetooth Speaker

![Bluetooth speaker connection](bluetooth-speaker.png)

### Office Tablet

![Office Tablet Bluetooth test](office-tablet.png)

### Tethering Web Test

![User-Laptop tethering web test](tether-access.png)

## Key Concepts

- WLAN
- SSID
- Pre-Shared Key
- Bluetooth
- Device Pairing
- Cellular Tethering
- DHCP
- Wireless Connectivity

## Lessons Learned

- WLAN connections require the correct SSID and pre-shared key before a client can join the network.
- Bluetooth devices must be discoverable and paired before they can communicate.
- Cellular tethering can provide network access to another device when traditional LAN or WLAN access is unavailable.
- Wireless troubleshooting depends on checking both connection status and IP addressing.
