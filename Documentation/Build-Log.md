# Build Log

---

## Build 001

### Date

7/10/26

### Objective

Prepare the primary administrator workstation for virtualization.

### Status

🟨 In Progress

### Lessons Learned

(To be completed)

Build 002

Objective

Deploy the first enterprise server.

Reason

A Domain Controller provides centralized authentication and identity management for the enterprise.

Expected Result

A functional Windows Server virtual machine ready for Active Directory deployment.

## Build 003

### Objective

Install Windows Server 2022 on DC-01.

### Installation Type

Custom (Clean Installation)

### Reason

The virtual hard disk is empty and does not contain an existing operating system. A clean installation is required to deploy a new Windows Server instance.

### Expected Result

Windows Server 2022 is installed on the virtual hard disk, and DC-01 boots successfully from the VDI instead of the ISO image.
## Build 003

### Status

✅ Windows Server installation completed successfully.

### Current Phase

Initial operating system configuration.

### Next Step

Configure the built-in Administrator account and sign in for the first time.
