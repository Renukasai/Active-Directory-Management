# Active-Directory-Management

**Overview**
---------------------------------------------------
This project focuses on the deployment and management of Active Directory (AD) in a secure environment. The setup includes the creation of a new AD forest, configuration of user accounts, and integration of network services such as DHCP and RAS/NAT to ensure seamless connectivity. The project was implemented in a virtualized environment, simulating real-world scenarios for managing users, devices, and resources effectively.

**Technologies and Tools Utilized**
-----------------------------------------------
-Active Directory: Deployed and managed user accounts, organizational units (OUs), and permissions for centralized network management.

-DHCP Configuration: Set up a DHCP server to automate IP address allocation across the network.

-RAS/NAT Setup: Configured Remote Access Service (RAS) and Network Address Translation (NAT) to enable secure remote access and inter-subnet communication.

-PowerShell: Automated the creation of multiple user accounts and administrative tasks, streamlining operations.

**Environments Used**
---------------------------
-Windows Server 2019: Configured Active Directory, DHCP, and RAS/NAT on the server platform.

-Oracle VirtualBox: Virtualization platform used to build and manage the environment, including client and server machines.

-Windows 10: Client operating system used to test domain connectivity and user login functionality.

**Project Walkthrough**
------------------------------------
**1. Installed Active Directory Domain Services (AD DS) and established a new forest with a root domain for centralized user management.**
   

<img width="398" alt="image" src="https://github.com/user-attachments/assets/3bc3dca6-7b8f-4493-8e97-3d5a3d9147b2" />


**2. Set up RAS and NAT for secure remote access and network routing.**


<img width="512" alt="image" src="https://github.com/user-attachments/assets/07738112-a0f1-4c9e-b24a-99b9605a024b" />


**3. Configured a DHCP server to provide dynamic IP address allocation to client machines.**


<img width="515" alt="image" src="https://github.com/user-attachments/assets/ebdf4cbe-7fed-42e4-8f94-dd9f665d2e46" />


**4. Created 1000 user accounts using PowerShell automation script.**


<img width="389" alt="image" src="https://github.com/user-attachments/assets/02878c24-154f-4421-bcfb-45ce1e2cabd2" />


**5. Finding Users**


<img width="510" alt="image" src="https://github.com/user-attachments/assets/08e93bec-5270-4557-bfbc-072777d34f4e" />


**6. Confirm Windows 10 Connectivity**


<img width="393" alt="image" src="https://github.com/user-attachments/assets/ded8ccc9-e5d9-4ea1-b9dc-69b384cd75f9" />


**7. Allocated IP addresses via DHCP, verifying the Windows 10 machine's domain connection in lease records.**


<img width="397" alt="image" src="https://github.com/user-attachments/assets/9e4a4aa5-37a9-4b1f-9387-ce73631d76a1" />


**8. Active Directory Users and Computers**


<img width="393" alt="image" src="https://github.com/user-attachments/assets/7531ab67-0c8f-4eed-982d-03f271ccd67b" />


**9. Testing and Validation: Successfully validated domain connectivity and login functionality for client machines using the newly created user accounts.**


<img width="299" alt="image" src="https://github.com/user-attachments/assets/a141f1c0-53cb-4f85-bcd8-4b4bda6414d1" />
    
