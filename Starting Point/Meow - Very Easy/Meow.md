![image](https://user-images.githubusercontent.com/94435318/161561175-85ea34cf-fc01-4ec8-bc88-3501953e7851.png)

![image](https://user-images.githubusercontent.com/94435318/161561268-a40561c7-1e02-4ec6-bc3e-775f90bd50d4.png)

# MEOW - VERY EASY

## Step-1 Connect to HTB

### Click Connect to HTB

![image](https://user-images.githubusercontent.com/94435318/161561644-cf88f96e-2a23-48a2-b28f-b606e7b6fcc6.png)

### Click OpenVpn

![image](https://user-images.githubusercontent.com/94435318/161561762-777be237-ccc3-45a5-9df5-8500f46eda69.png)

### Download VPN

![image](https://user-images.githubusercontent.com/94435318/161561916-87f6fd74-b246-4c24-99c5-c8a6d18573ac.png)

### Go to Downloads -> Open terminal here -> sudo openvpn (downloaded file name.ovpn)

![image](https://user-images.githubusercontent.com/94435318/161562203-d80966ed-7fcc-4ec9-9b16-f6994084f7b8.png)

### Vpn Connected

![image](https://user-images.githubusercontent.com/94435318/161563110-feb7219e-e1c9-40f0-a49b-d83c16dd5036.png)

## Step-2 Spwan Machine

### Click Spawn Machine button 

![image](https://user-images.githubusercontent.com/94435318/161563287-1f07f287-4a57-4fa9-aa22-ff8d6a2d2116.png)

![image](https://user-images.githubusercontent.com/94435318/161563503-2173df4b-2b14-462f-8abf-c59cadebddc6.png)

## Step-3 Submit the flags

### Task-1

What does the acronym VM stand for? 

Answer: Virtual MAchine (Our machine is run in virtual only)

### Task-2

What tool do we use to interact with the operating system in order to start our VPN connection? 

Answer: Terminal (we use terminal for connecting openvpn in kali linux)

![image](https://user-images.githubusercontent.com/94435318/161564677-713da972-7757-48ef-9748-d1ad3f7d483a.png)

### Task-3

What service do we use to form our VPN connection? 

Answer: openvpn (we download it in htb machine)

### Task-4

What is the abreviated name for a tunnel interface in the output of your VPN boot-up sequence output? 

Answer: tun

![image](https://user-images.githubusercontent.com/94435318/161565374-31668257-8f13-43cb-bcac-1bf55177ea2c.png)

### Task-5

What tool do we use to test our connection to the target? 

Answer: ping  (ping the ip given by htb machine, to check whether our target get ping or not)
 
![image](https://user-images.githubusercontent.com/94435318/161566051-d481a239-0009-4dea-890b-6d6ce32b688f.png)

### Task-6

What is the name of the tool we use to scan the target's ports? 

Answer: nmap (nmap is used to scan the ip to check the open ports)

![image](https://user-images.githubusercontent.com/94435318/161566758-b5ab77e4-4c3e-44df-9d6f-89b44c07afda.png)

### Task-7

What service do we identify on port 23/tcp during our scans? 

Answer: telnet

![image](https://user-images.githubusercontent.com/94435318/161566918-fd3baffc-20d7-4e0f-8652-968e1cac1475.png)

### Task-8

What username ultimately works with the remote management login prompt for the target? 

Answer: root

![image](https://user-images.githubusercontent.com/94435318/161567518-d271df99-57bc-4237-88b3-12a43b78da90.png)

### Submit Flag

Submit root flag 

Answer: b40abdfe23665f766f9c61ecba8a4c19

![image](https://user-images.githubusercontent.com/94435318/161568046-9418a83a-f5cf-4110-b35f-2130e8aadba4.png)

![image](https://user-images.githubusercontent.com/94435318/161567964-cc20c8f9-04b1-4f38-8ef1-71e40abc27db.png)
