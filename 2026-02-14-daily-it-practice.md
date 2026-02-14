**📅 Daily IT Practice — February 14, 2026**

**📝 Overview**
Today I completed Module 4 of the Google IT Support Professional Certificate, focusing on Filesystem Types. 
I worked through two hands‑on labs: partitioning and formatting disks in Windows and Linux. 
I practiced GUI‑based disk management, low‑level partitioning with fdisk, formatting with different file systems, and mounting new partitions. 
This session strengthened my understanding of storage management across both operating systems.

**🎯 What I Completed Today**
• 	Finished Lab 01 — Partitioning and Formatting a Disk Drive in Windows
• 	Finished Lab 02 — Partitioning and Formatting a Disk Drive in Linux
• 	Completed all objectives for both labs
• 	Practiced essential disk utilities and commands
• 	Reinforced filesystem concepts from Module 4

**🛠️ Tools, Commands & Utilities Practiced**
**Windows**
• 	Disk Management (diskmgmt.msc)
• 	Control Panel → Administrative Tools → Computer Management
• 	Partitioning & formatting via GUI
**Linux**
- lsblk
- df -h
- sudo fdisk /dev/<device>
- mkfs -t ext4
- mount
- Partition type changes (Linux swap)

**📂 Lab Summaries
🧩 Lab 01 — Windows Disk Partitioning**
• 	Brought an offline disk online
• 	Shrunk an existing volume
• 	Created two partitions (30GB NTFS, 20GB FAT32)
• 	Formatted the second partition
• 	Verified final disk layout
**🧩 Lab 02 — Linux Disk Partitioning**
• 	Identified mounted vs unmounted block devices
• 	Deleted 12 default partitions on 
• 	Created a 1GB swap partition and a 9GB ext4 partition
• 	Formatted  as ext4
• 	Mounted it to 
• 	Verified mount points

**🐞 Problems & Fixes**
• 	Windows VM delay → waited for environment to load
• 	Multiple default partitions on Linux disk → removed all using 
• 	Ensuring correct device selection → used  and  to avoid mistakes

📚 What I Learned Today
• 	How Windows and Linux handle disk partitioning differently
• 	How to safely modify partitions without damaging mounted systems
• 	How to use  interactively to delete, create, and modify partitions
• 	How to format partitions using NTFS, FAT32, and ext4
• 	How to mount new Linux file systems and verify them
• 	Why partition types matter (swap vs data partitions)
• 	Reinforced confidence with low‑level storage commands

**📎 Related Files**
- lab01-partitioning-and-formatting-windows.md
- lab02-partitioning-and-formatting-linux.md

**➡️ Next Steps**
• 	Complete Module 4 readings
• 	Start Module 4 challenge: Filesystems
• 	Prepare for Module 5: Process Management
• 	Continue practicing Linux disk utilities to build muscle memory
