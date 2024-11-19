# VIRTUAL MACHINE CREATION IN LINUX
## AIM
   To Install Virtualbox / VMware Workstation with different flavours of linux.
   
## PROBLEM STATEMENT
   This experiment involves setting up a virtual machine with CentOS, a popular Linux distribution. This setup allows users to practice Linux commands, test applications, and develop software in a virtualized environment without affecting the host system.

## ALGORITHM

Step 1: Open VirtualBox or VMware Workstation

Step 2: Go to File -> New to create a new virtual machine.

Step 3: Enter a name for your CentOS VM.Choose Linux as the type and CentOS as the version (or select the closest option available if CentOS is not listed).

Step 4: Select the CentOS ISO image you downloaded. Set the base memory to 1024 MB (1 GB) Allocate 1 processor core Set the disk size to at least 20 GB Complete the configuration by clicking Finish to create the virtual machine

Step 5: Select the created VM, go to Details (or Settings), and navigate to the Network tab. Configure Adapter 1 as NAT (for internet access through the host). Configure Adapter 2 as Bridged Adapter (for direct access to the local network, if needed). Click OK to save network settings.

Step 6: Click Start to boot up the newly created virtual machine. During installation, set a password for the root user. After logging in to CentOS, open a terminal to start using the command line.

## COMMANDS

## Switch to User:
```su username```

## View IP Address:
```ip a```

## Create a Directory:
```mkdir <directory_name>```

## Change to the New Directory:
```cd <directory_name>```

## Edit the Hostname File:
```vi /etc/hostname```

## View the Content of the Hostname File:
```cat /etc/hostname```

## OUTPUT

### REG NUMBER: 212223040066
### NAME: HEMAPRIYA K

![386475833-130d3692-0779-4ee4-b312-495f498dd63c](https://github.com/user-attachments/assets/6e2ab8c3-57ae-40da-b5bf-84028e462a7c)

![386475850-4ae93d29-2820-4c85-9cab-e96344d6f3cf](https://github.com/user-attachments/assets/6a99ce5d-0748-4618-8323-ea73a6eb3a10)

 

## RESULT
The Installation of Virtualbox / VMware Workstation with different flavours of linux is successfully created .
 

  


