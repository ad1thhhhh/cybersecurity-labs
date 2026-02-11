# Setting Up My First Cybersecurity Lab

## Objective
To build a personal cybersecurity lab to practice SOC, DFIR, and safely run scans and scripts without worrying about disrupting my personal device.

## Tools & Software Used
- VMware Workstation / VirtualBox
- Windows 10 VM (for SOC labs)
- Ubuntu Linux VM (for scripting and basic security testing)
- Parrot OS VM (for penetration testing and security tools)
- Autopsy, Wireshark, Sysinternals

## Steps Performed
1. Installed VMware Workstation and set up a virtual network.
2. Created a Windows 10 VM and updated it with all security patches.
3. Created an Ubuntu VM for Linux-based security tools.
4. Created a Parrot OS VM for ethical hacking and penetration testing.
5. Tested connectivity and isolated the lab from my host network.
6. Installed security tools like Autopsy, Wireshark, and Parrot OS pre-installed tools.
7. Documented configurations, IP ranges, and lab topology.

## Challenges Faced
- Networking between VMs initially didn’t work — resolved with NAT + Host-only settings.
- Resource allocation caused VMs to run slowly — optimized RAM and CPU.

## What I Learned
- How to create isolated lab networks
- Installing and configuring VMs for security practice
- Planning lab topology for SOC, DFIR, and ethical hacking
- Importance of documentation for reproducibility

## Next Steps
- Add a Windows Server VM for AD and group policy experiments
- Practice SOC monitoring using Windows Event Logs
- Simulate incidents and run forensic investigations
- Explore more Parrot OS tools for penetration testing
