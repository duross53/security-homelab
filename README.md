First Cybersecurity HomeLab 

## Objective
Build a safe, isolated home cybersecurity lab to practice offensive and defensive security techniques using virtual machines.

## Environment
- Host OS: Windows 10
- Hypervisor: Oracle VirtualBox
- Attacker Machine: Kali Linux
- Target Machine: Windows 10
- Network Type: Host-only Adapter
- Subnet: 192.168.56.0/24

## Initial Setup
- Installed VirtualBox on Windows host
- Imported Kali Linux virtual machine
![kali VM](https://github.com/user-attachments/assets/e7d18302-880a-4d36-b926-4e915bd33717)
- Created Windows 10 virtual machine
![Windows VM](https://github.com/user-attachments/assets/6abf7ca2-a88b-4f57-a99d-d0a0841f5521)
- Configured both VMs to use a Host-only network
![adapter settings](https://github.com/user-attachments/assets/042cc638-aa68-4838-9c72-5403c366f535)

## Networking Configuration
- Enabled Host-only DHCP in VirtualBox Host Network Manager
![network settings](https://github.com/user-attachments/assets/c1ed734a-c91d-447c-ae1c-2950d3d43bdf)
- Assigned IPv4 addresses via DHCP

### IP Addressing
- Kali Linux: `192.168.56.101`
- Windows 10: `192.168.56.102`

## Verification
- Verified IP addresses using:
  - `ip a` (Kali)
  - `ipconfig` (Windows)
- Successfully tested connectivity using ICMP:
  - Kali → Windows (`ping 192.168.56.102`)

## Snapshot
Created a clean baseline snapshot for both virtual machines
![vbox](https://github.com/user-attachments/assets/0949dac1-b29d-4312-99dc-d7688813d7da)
- Description:
  Initial lab baseline with functional host-only networking and verified VM-to-VM connectivity. No scans, attacks, or configuration changes performed.

## Skills Demonstrated
- Virtual machine setup and management
- VirtualBox networking (Host-only, DHCP)
- IPv4 troubleshooting
- Linux networking commands
- Windows networking diagnostics
- Lab documentation and snapshot management

## Outcome
Successfully deployed a functional home cybersecurity lab ready for future attack and defense exercises.
