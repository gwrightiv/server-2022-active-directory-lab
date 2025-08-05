# Folder Redirection via Group Policy

## Overview
Redirected domain user Documents folder to a network share hosted on the server using a Group Policy Object (GPO).

## Steps Taken
1. Created `C:\GrahamRedirection` and shared it with Everyone (read/write).
2. Created a GPO named "Folder Redirection" and linked it to the domain.
3. Configured redirection of the Documents folder:
    - Basic redirection for all users
    - Root path: `\\DC001\GrahamRedirection`
    - User-exclusive rights and move contents enabled
4. Applied GPO with `gpupdate /force`
5. Logged into the Windows 11 client and verified:
    - File properties pointed to network share
    - Server-side folder showed redirection

## Screenshot Highlights
- Folder sharing tab
- GPO redirection target and settings
- Properties of redirected file
- Access denied to server-side document folder

## Notes
Illustrates GPO usage for desktop experience consistency and centralized storage.
