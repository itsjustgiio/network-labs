# Structured Cabling Simulation

## Objective

Build a structured office cabling layout that connects workstations to a wiring closet through wall ports and a patch panel.

## Description

Created an office cabling layout in Cisco Packet Tracer using a wiring closet, rack-mounted patch panel, wall mounts, switch connections, and copper cabling. Connected office devices through wall ports and punchdown connections instead of directly cabling each device to the switch, matching how a real office network is commonly organized and maintained.

## Topology

![Structured cabling physical topology](topology.png)

## Network Components

- Office-SW1
- Patch Panel0
- Wall Mount0 and Wall Mount1
- Office-Admin PC
- Office-User PC
- Printer0
- Office-Server

## Skills Demonstrated

- Cisco Packet Tracer
- Structured Cabling
- Patch Panel Termination
- Wall Port Connectivity
- Copper Cabling
- Wiring Closet Layout
- Cable Management
- DHCP Verification
- LAN Connectivity Testing

## Tasks Performed

- Installed a patch panel in the wiring closet rack
- Connected switch ports to patch panel jacks
- Added wall mounts in the office
- Linked wall mount punchdowns back to the patch panel
- Connected PCs and a printer through wall jacks
- Verified DHCP addressing and access to `office.srv`
- Organized cables using rack management and bendpoints

## Verification

Both office PCs received network addressing and were able to reach the internal web server at `office.srv`.

### Equipment Cabinet

![Equipment cabinet and patch panel cabling](equipment-cabinet.png)

### Office-Admin IP Configuration

![Office-Admin IP configuration](office-admin-ip.png)

### Office-Admin Web Test

![Office-Admin office.srv test](office-admin-web-test.png)

### Office-User IP Configuration

![Office-User IP configuration](office-user-ip.png)

### Office-User Web Test

![Office-User office.srv test](office-user-web-test.png)

## Key Concepts

- Structured Cabling
- Wiring Closet
- Patch Panel
- Wall Ports
- Punchdown Connections
- Cable Management
- DHCP
- LAN Connectivity

## Lessons Learned

- Patch panels help organize switch connections and make office cabling easier to manage.
- Wall ports let end devices connect to the network without running long cables directly to the switch.
- Punchdown mappings need to match the correct patch panel ports for devices to receive connectivity.
- Clean cable management makes physical network layouts easier to troubleshoot and document.
