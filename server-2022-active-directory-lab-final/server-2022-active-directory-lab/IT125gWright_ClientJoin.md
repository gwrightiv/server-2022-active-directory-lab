# Joining a Windows 11 Client to the Domain

## Overview
A Windows 11 virtual machine was joined to the `gwright.local` domain.

## Key Steps
1. Ensured DNS on the client pointed to the domain controller.
2. Used Control Panel → System → Change Settings → Domain Join.
3. Supplied domain admin credentials (`Admin / NotEnsign#125!`).
4. Verified domain join with system properties and PowerShell.

## Screenshot Highlights
- Control panel domain join process
- Successful login screen for domain user
- `Get-WmiObject` domain membership output

## Notes
This demonstrated client-server communication, DNS configuration, and credential-based authentication in a domain environment.
