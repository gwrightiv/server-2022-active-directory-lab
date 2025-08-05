# Subnetting & Network Testing

## Overview
Designed and implemented subnetting plans for `192.168.4.0/24` network, then verified connectivity between subnets.

## Subnet Examples
- /24: Full range (254 hosts)
- /25, /26, /27, /28, /29, /30: Used to allocate segments for various departments and routers

## Scenario Breakdown
| Department     | Hosts | CIDR | Subnet       | Mask              |
|----------------|-------|------|--------------|-------------------|
| Sales          | 80    | /25  | 192.168.110.0| 255.255.255.128   |
| Advertising    | 35    | /26  | 192.168.110.128| 255.255.255.192 |
| Research       | 18    | /27  | 192.168.110.192| 255.255.255.224 |
| Marketing      | 11    | /28  | 192.168.110.224| 255.255.255.240 |
| Administration | 6     | /29  | 192.168.110.240| 255.255.255.248 |
| CEO            | 2     | /30  | 192.168.110.248| 255.255.255.252 |
| Router→Router  | 2     | /30  | 192.168.110.252| 255.255.255.252 |

## Ping Testing
- Documented ping failures and corrections due to subnet mismatch.
- Successful ping achieved by aligning both VMs to the same /26 subnet.

## Notes
Reinforces understanding of subnet math and practical implications of IP allocation.
