# Lab 14: Network Configuration & DNS Diagnostics

## Objective

Troubleshoot IP connectivity, network routes, local hostname resolution, and domain name lookup configurations.

---

## Networking Diagnostics

### 1. Interface & IP Verification
- Audited active network interfaces and IP bindings using `ifconfig` / `ip addr`.
- Verified local system routes using `route -n` or `ip route`.

### 2. Connectivity & DNS
- Tested gateway reachability using `ping`.
- Verified host resolution via `/etc/hosts` and external domain queries via `dig` and `nslookup`.
