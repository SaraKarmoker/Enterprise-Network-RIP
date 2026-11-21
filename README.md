# Design and Simulation of an Enterprise Network using RIP

Cisco Packet Tracer project for the Computer Network PBL.

## What it has
- Head Office with 4 departments (HR, IT, Finance, Sales) and a server room
- Branch Office and an ISP router
- VLANs and router-on-a-stick (inter-VLAN routing)
- DHCP and DNS/Web servers
- RIPv2 between HQ-R1 and Branch-R2
- NAT for Internet access
- Security: ACL (Sales blocked from Finance), port security, SSH

## IP plan
| Network | Address |
|---|---|
| HR (VLAN 10) | 192.168.10.0/24 |
| IT (VLAN 20) | 192.168.20.0/24 |
| Finance (VLAN 30) | 192.168.30.0/24 |
| Sales (VLAN 40) | 192.168.40.0/24 |
| Servers (VLAN 50) | 192.168.50.0/24 |
| Branch LAN | 192.168.60.0/24 |
| HQ to Branch link | 10.0.12.0/30 |
| Branch to ISP link | 10.0.23.0/30 |

## Files
- `Enterprise_Network_RIP.pkt` - open with Cisco Packet Tracer
- Screenshots of the topology and test results
