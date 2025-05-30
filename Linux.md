Linux and System Administration:
    
    Soft and Hard link difference
    
    Significance or use of inode
    
    How to check files older than 20 days
    
    How to check open ports in Linux
    
    Check the total number of inodes
    
    What does the df command do?
    
    What are the types of files in Linux?
    
    How to check open ports
   
    Default Network types in Docker - Have you heard about bridge host?
    
    How to check container logs
    
    How to check open ports
    
    Docker port command


Linux Interview Questions
1. What is LVM in Linux? 
2. What are the main components of LVM? 
3. What is the purpose of an LVM snapshot? 
4. What are the advantages of using LVM? 
5. How do you create an LVM setup from scratch? 
6. How do you resize a logical volume? 
7. How do you display LVM information? 
8. What is a striped logical volume? 
9. How do you create an LVM snapshot? 
10. What is thin provisioning in LVM? 
11. How do you remove an LVM configuration? 
12. What is the difference between linear and striped volumes? 
13. How do you replace a failing disk in an LVM setup? 
14. What happens if an LVM volume is full? 
15. How do you recover a deleted logical volume? 
16. How do you troubleshoot an issue with an LVM volume not mounting? 
17. What steps would you take if pumove fails during migration? 
18. How do you fix an inactive logical volume? 
19. How do you repair corrupted LVM metadata? 
20. What are the common causes of LVM performance issues, and how do you resolve them?
 
	*******Linux admin interview questions and answers******* 
	 
1. Explain the Linux boot process?
	Ans: The BIOS loads the bootloader (like GRUB), which loads the kernel. The kernel initializes hardware, mounts the root filesystem, and starts 'init' or 'systemd', loading system services and setting the default runlevel or target. 
2. How would you troubleshoot a slow server?
	Ans: Check system resources ('top', 'vmstat', 'free') for CPU, memory, or 1/0 issues. Review disk usage ('df", 'du') and network traffic ('netstat', 'ss'). Identify resource-heavy processes and adjust configurations, terminate processes, or consider hardware upgrades. 
3. Describe Linux file permissions and how to change them?
	Permissions include read, write, and execute for the owner, group, and others. Use 'chmod' to modify permissions (e.g., 'chmod 755 filename"), 'chown' to change ownership, and 'chgrp' to change the group. 
4. What is LVM, and how do you manage it?
	LVM (Logical Volume Manager) enables flexible disk management across physical volumes. Commands include pvcreate' (create physical volume), 'vgcreate' (create volume group), 'Ivcreate* (create logical volume), and 'Ivextend'/ 'Ivreduce for resizing. 
5. How do you secure a Linux server?
	Disable unnecessary services, configure 'iptables /'firewalld enforce SSH security (disable root login, use SSH keys), enable SELinux/AppArmor, apply patches, monitor logs, and use Fail2ban for brute-force prevention. 
6. How do you manage services in Linux?
	Use 'systemctl' for 'systemd' services ('systemctl start service' 
	'systemctl enable service*). On older systems, use 'service or 'init.d' scripts. 
7. How do you add a user and manage permissions?
	Use 'useradd username' and 'passwd username' to add users. Add users to groups with 'usermod -aG groupname username' ' Adjust file permissions with 'chmod' and 'chown'. 
8. How do you monitor server performance?
	Use 'top' or 'htop' for real-time monitoring, 'sar' for historical data, 
	, "iostat' for 1/0 stats, and 'netstat' or 'ss' for network connections. Monitor load average, keeping it below the number of CPU cores. 
9. What steps would you take for filesystem corruption recovery?
	Boot into single-user mode or use a live CD, run 'isck' to repair, and restore from backups if needed. Regular backups are essential for data protection. 
10. How do you automate tasks in Linux?
	Use 'cron' for scheduled tasks ('crontab -e*). For complex automation, use shell scripts and tools like 'Ansible' or 
	'Puppet' for consistent deployments across servers. 
11. Difference between Is and Il commands in Linux: 
	Is: Lists the files and directories in the current directory. 
	II: It's typically an alias for Is -1, which provides a detailed listing (permissions, owner, group, size, and timestamp). 
12. Find the IP address of a Linux machine: 
	1. You can use ip addr show or ifconfig to find the IP address. 
	For example, run ip a or ifconfig to view the IP address of the machine. 
13. What does the chmod command do? 
	1. The chmod command changes the file permissions. The numeric representation of file permissions is: 
	4: Read (r) 
	2: Write (W) 
	1: Execute (x) The sum of these numbers defines the permissions: 
	4.7 (rwx): Full permissions (read, write, execute) 
	6 (rw-): Read and write 
	5 (r-x): Read and execute 
	4 (r--): Read only 
14. List all files in a directory, including hidden ones: 
	Use Is -a to list all files, including hidden files (those starting with a dot). 
15. Check disk space usage in Linux: 
	Use df -h to display disk space usage in a human-readable format. 
16. Difference between a hard link and a symbolic link: 
	A hard link is another name for an existing file, pointing to the same inode. Deleting one does not affect the other. 
	A symbolic link (symlink) is a pointer to another file or directory and can span across file systems. If the original file is deleted, the symlink breaks. 
	Hard links point directly to the inode; soft links are shortcuts to the file path. 
17. Check running processes in Linux: 
	Use ps aux or top to check running processes. 
18. Difference between kill and killall commands: 
· kill: Sends a signal to a process by its PID (Process ID). 
· killall: Sends a signal to all processes with the specified name. 
19. Bring a background process to the foreground: 
	Use fg to bring a background process to the foreground. 
20. Create a new user in Linux: 
	Use the useradd command followed by the username, for example: sudo useradd username. 
21. Purpose of the /etc/passwd file: 
	It stores user account information, including username, UID (user ID), GID (group ID), home directory, and shell. 
22. Change the password for a user in Linux: 
	Use passwd username to change a user's password. 
23. Configure a static IP address in Linux: 
	You can edit the network configuration file (e.g., /etc/network/ interfaces for Debian-based systems or /etc/sysconfig/network-scripts/ifcg-ethO for RedHat-based systems). 
24. Difference between ping and traceroute commands: 
	ping: Tests connectivity between the source and destination. 
	traceroute: Shows the path that packets take to reach a destination, helping diagnose routing issues. 
25. Function of the ifconfig command in Linux: 
	ifconfig is used to configure or display network interfaces, IP addresses, and other network settings. 
26. Explain the Linux boot process: 
	BIOS/UEFI initializes hardware. Bootloader (GRUB) loads the kernel. Kernel initializes hardware and mounts the root filesystem, then starts init or systemd. 
27. How do you manage disk partitions in Linux? 
	Use tools like fdisk, parted, or gparted to create, modify, or delete partitions. Update /etc/stab for automatic mounting. 
28. What are inodes in Linux? 
	Inodes store metadata about files, such as permissions, ownership, and timestamps, but not the file name or data. 
29. How do you check system uptime and load average? 
	Use uptime or top commands. Load average shows the number of processes waiting for CPU. 
30. What is the purpose of the /etc/fstab file? 
	It defines filesystems and their mount points for automatic mounting at boot. 
31. How do you change the hostname of a Linux system? 
	Use hostnamectl set-hostname <new_hostname> or edit /etc/ hostname and /etc/hosts. 
32. What is the difference between cron and anacron? 
	Cron schedules recurring tasks but requires the system to be on. Anacron runs missed tasks when the system is powered on. 
33. How do you troubleshoot file permission issues? 
	Check permissions with Is -I. Use chmod, chown, or setfacl to correct permissions. 
34. What is the difference between df and du commands? 
	df shows filesystem usage, while du shows directory/file disk usage. 
35. Explain the Linux Boot Process 
	Steps: BIOS → Bootloader (e.g., GRUB) → Kernel → Init/Systemd → Services/Runlevel. 
	Purpose: Initializes hardware, mounts root filesystem, starts user-space processes.
	Mention that UEFI is often used instead of BIOS in modern systems. 
	Add clarification about initramfs, which is loaded by the bootloader to prepare the actual root filesystem.  
36. Troubleshooting a Slow Server 
	Check: top, vmstat, free (CPU, memory), df (disk), ss/netstat (network). 
	Action: Optimize processes, terminate resource hogs, or upgrade hardware. 
	Network traffic is checked using iftop or nload in addition to netstat and ss. 
	Mention logs (dmesg, journalctl, or application-specific logs) to identify possible causes. 
37. Securing a Linux Server 
	Steps: 
	Disable unused services. 
	Configure iptables/firewalld. 
	Enforce SSH security (disable root login, use SSH keys). 
	Enable SELinux/AppArmor. 
	Patch regularly. 
	Use Fail2ban for brute-force protection. 
	Specify encryption practices (e.g., encrypting sensitive data and filesystems using LUKS or gpg). 
	Mention using intrusion detection tools like AIDE or Tripwire. 
38. Managing Services 
	Commands: systemctl (start, enable services). 
		Legacy: service or /etc/init.d/. 
39. Adding Users and Managing Permissions 
	Commands: 
	Add: useradd username, passwd username. 
	Groups: usermod -aG groupname username. 
	Permissions: chmod, chown. 
40. Monitoring Server Performance 
	Tools: 
	Real-time: top, htop. 
	Historical: sar. 
	Disk: iostat. 
	Network: ss, netstat. 
41. Filesystem Corruption Recovery 
	Steps: Boot in single-user mode or live CD → Run fsck → Restore from backups. 
	Preventive: Regular backups.
	Highlight the importance of mounting partitions as read-only during recovery. 
Specify using backup utilities (e.g., rsync, tar, or bacula) to maintain regular backups
