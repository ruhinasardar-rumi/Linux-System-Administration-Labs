# Lab 16: User & Group Administration

## Objective

Provision user accounts, configure secondary group memberships, set password policies, and customize default user templates.

---

## Account Lifecycle Management

### 1. User & Group Provisioning
- Created users (`useradd`) and groups (`groupadd`).
- Modified account parameters and assigned secondary groups (`usermod -aG`).

### 2. Default Configurations
- Inspected `/etc/passwd`, `/etc/group`, and `/etc/shadow`.
- Tailored system-wide default account settings in `/etc/default/useradd`.
