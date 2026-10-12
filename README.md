# Linux Remote Access and Secure File Transfer Lab

## Project Overview

This project demonstrates how to establish secure remote access from WSL Linux on a Windows host to a Kali Linux virtual machine using SSH.

It also demonstrates how to transfer files between the two environments using SCP and troubleshoot basic network connectivity issues.

## Objectives

- Understand the client-server model of SSH.
- Configure and verify the OpenSSH server on Kali Linux.
- Connect remotely from WSL to Kali Linux.
- Upload and download files using SCP.
- Test network connectivity and SSH port accessibility.
- Document troubleshooting procedures and results.

## Lab Environment

- Host operating system: Windows
- Linux client: WSL Linux
- Virtualization platform: Oracle VirtualBox
- Remote machine: Kali Linux
- Remote access protocol: SSH
- File transfer utility: SCP

## Tasks Performed

### 1. SSH Service Verification

Verified the SSH service status on Kali Linux and confirmed whether it was listening for incoming connections.
<img width="813" height="653" alt="image" src="https://github.com/user-attachments/assets/56ad727a-bb0c-403f-8f87-54181fb4c1aa" />


### 2. Remote Access

Initiated an SSH connection from WSL to Kali Linux using the remote username and IP address.
<img width="917" height="431" alt="image" src="https://github.com/user-attachments/assets/c0e392bd-73b8-4882-a3f1-4e4eb10ac028" />


### 3. File Transfer: WSL to Kali

Created a test file in WSL, transferred it to Kali using SCP, and verified the file contents on the remote machine.
<img width="983" height="556" alt="image" src="https://github.com/user-attachments/assets/4cf2ae5e-1b6a-4846-95b7-53f48d05374d" />
<img width="832" height="466" alt="image" src="https://github.com/user-attachments/assets/9043219c-c120-436e-9733-9977506129b0" />


### 4. File Transfer: Kali to WSL

Created a test file on Kali, downloaded it to WSL using SCP, and verified the transferred content.
<img width="752" height="152" alt="image" src="https://github.com/user-attachments/assets/6cf7d42a-65c8-4090-b9bb-d66ae6dc183d" />
<img width="833" height="340" alt="image" src="https://github.com/user-attachments/assets/566d5425-e62b-484e-a742-8657ec59417d" />



### 5. Network Troubleshooting

Used networking commands to test IP connectivity, check TCP port 22 and investigate SSH connection issues.
<img width="867" height="390" alt="image" src="https://github.com/user-attachments/assets/b5ed25f7-3917-47ef-b924-1936f225096f" />
<img width="748" height="380" alt="image" src="https://github.com/user-attachments/assets/50343333-dc63-4bf8-a8d1-34343e4de61b" />



## Evidence

Screenshots documenting the lab environment, SSH connection, file uploads, file downloads and connectivity tests are stored in the `screenshots/` directory.

## Skills Demonstrated

- Linux command-line fundamentals
- SSH remote administration
- SCP file transfers
- Basic TCP/IP troubleshooting
- Linux service management
- Virtual machine lab setup
- Technical documentation

## Lessons Learned

This lab helped me understand how SSH provides remote command-line access, how SCP transfers files over SSH, and how network connectivity and service availability affect remote administration.

## Project Status

Update this section to reflect the tasks actually completed and tested.

## Future Improvements

- Configure SSH key-based authentication.
- Compare NAT, host-only and bridged networking.
- Practise additional SSH troubleshooting scenarios.
- Automate file transfers using shell scripts.
