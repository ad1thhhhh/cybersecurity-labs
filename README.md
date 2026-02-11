# Setting Up My First Cybersecurity Lab

## Objective
To build a personal cybersecurity lab to practice SOC, DFIR, and safely run scans and scripts without worrying about disrupting my personal device.

## Tools & Software Used
- Oracle VirtualBox
- Windows 10 VM (for SOC labs) used as a Target VM
- Ubuntu Linux VM (for scripting ) used as an offensive VM
- Parrot OS VM (for penetration testing and security tools) used as a defensive VM
- Autopsy, FTK Imager

## Steps Performed
1. Installed Oracle VirtualBox and set up a virtual network. 
2. Created a Windows 10 VM and updated it with all security patches.  
3. Created a Kali Linux VM for Linux-based security tools.
4. Created a Parrot OS VM for ethical hacking and penetration testing.

## Network Configuration
This lab environment uses a dual-adapter network setup to simulate a realistic and isolated cybersecurity testing environment.

### VM Network Setup

Each virtual machine (Kali, Parrot OS, Windows 10) is configured with:

- **Adapter 1: NAT**
  - Provides internet access for updates and tool installation.
  - MAC Address example: `080027F6E77A`

- **Adapter 2: Host-Only Adapter**
  - Creates a private lab network between all VMs.
  - Used for attack/defense simulations and internal communication.
  - MAC Address example: `080027F4QO72`

## Challenges Faced
- Networking between VMs initially didn’t work — resolved with NAT + Host-only settings.
- Resource allocation caused VMs to run slowly — optimized RAM and CPU.

- 
## What I Learned
- How to create isolated lab networks
- Installing and configuring VMs for security practice
- Planning lab topology for SOC, DFIR, and ethical hacking
- Importance of documentation for reproducibility

## Screenshots/Notes
### Oracle Virtual Box
<img width="1918" height="1018" alt="image" src="https://github.com/user-attachments/assets/e978c045-a20d-48a9-94c3-dd93371a4731" /> 

### Windows - Victim VM
<img width="1022" height="876" alt="image" src="https://github.com/user-attachments/assets/6c931e38-21c5-4781-b9be-a2dc4555c53a" />

### Kali Linux VM - Attacker VM
<img width="802" height="603" alt="image" src="https://github.com/user-attachments/assets/800a762e-d54d-4bda-8fa8-fef04087dab0" />

### ParrotOS - Defense VM
<img width="1918" height="1016" alt="image" src="https://github.com/user-attachments/assets/b38cc18c-345b-4ee0-b923-5b5fb907278a" />

