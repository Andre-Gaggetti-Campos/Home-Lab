# Parts and Service 

[Back to Read Me](../README.md)

This section is not as important to read as the others. However, it will serve as a study guide for myself when it comes to parts and services I have researched.

## So, what am I looking for?

The Home Lab should be fully self contained with the ability to logically and physically be separated into vlans.

Currently this is the current idea:

External Router
|
Router/Firewall
|
Managed Switch
|
Vlans
- Wifi Vlan
    - Wireless Access Point
- Device Vlan
    - Mini PC
    - Running proxmox
- Management Vlan
    - Mini PC
    - Running proxmox
    - Running security and logger systems
- Server Vlan
    - Mini PC
    - Running server