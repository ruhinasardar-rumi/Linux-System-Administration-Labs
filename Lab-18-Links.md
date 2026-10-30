# Lab 18: Special Permissions, Links & Inodes

## Objective

Understand file system structures, configure directory sticky bits, and create Hard vs Symbolic (Soft) links.

---

## File System Tasks

### 1. Link Types & Inodes
- Created symbolic links using `ln -s` and hard links using `ln`.
- Verified file Inode numbers and link counts using `ls -i` or `ls -l`.

### 2. Special Permissions
- Configured sticky bits on shared directories (`chmod +t`) to restrict unauthorized file deletion.
