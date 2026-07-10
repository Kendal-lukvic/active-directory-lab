# Network Architecture

## Current Architecture

                     Internet
                         │
                    Home Router
                         │
        ┌────────────────┴────────────────┐
        │                                 │
 IT-ADMIN-01                      CLIENT-01
 Windows 11 Home                  Windows Client
 (Primary Admin PC)               (Employee PC)
        │
        │
        ▼
      DC-01
 Windows Server 2022
 Domain Controller

---

## Device Roles

### IT-ADMIN-01

Primary administrator workstation.

Hosts the virtual infrastructure.

---

### CLIENT-01

Enterprise employee workstation.

Used to test:

- Domain Join
- User Authentication
- Group Policy
- Password Management

---

### LAB-HOST-01

Expansion computer used for:

- Additional servers
- SIEM
- Linux
- Cybersecurity labs
