# Incognito
A simple *yet classy* rootkit for simple *yet classy* folks. 

**Authors:** 
Kordell Stewart, Suvaion Das, Alex Hassenbein  

This basic rootkit works on the Linux operating system and is a loadable kernel module which when loaded into the kernel (by the attacker with root privileges) will do the following:

  - Grant root privileges to a userland process
  - Hide process by PID
  - Unhide a previously hidden process by PID
  - Hide files or directories by their name
  - Unhide previously hidden files or directories
  - Hide itself
  - Unhide itself
  - Protect against being unloaded by the user
  - Disable the unload protection
  
 # Requirements 
 Created and tested on Distro: Ubuntu 18.04.1 LTS Kernal: 4.15.0-39-generic
  
 # Resources
 Here's some helpful guides, manuals, and links we used on this project 
- https://www.idontnix.net/tech/anaroot.html
- https://uwnthesis.wordpress.com/2016/12/26/basics-of-making-a-rootkit-from-syscall-to-hook/
- https://www.kernel.org/doc/htmldocs/kernel-hacking/routines-module-use-counters.html
- http://www.ouah.org/LKM_HACKING.html
- https://stackoverflow.com/questions/2103315/linux-kernel-system-call-hooking-example
- http://books.gigatux.nl/mirror/networksecuritytools/0596007949/networkst-CHP-7-SECT-2.html
