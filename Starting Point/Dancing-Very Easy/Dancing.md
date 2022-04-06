# DANCING - VERY EASY
----------------------------------------------------------------------------------------------------------------

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161561175-85ea34cf-fc01-4ec8-bc88-3501953e7851.png">
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161985229-8e70b1c5-0828-45ac-ba39-a2db03582e41.png">
</p>

## Step-1 Connect to HTB

### Click Connect to HTB

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161561644-cf88f96e-2a23-48a2-b28f-b606e7b6fcc6.png">
</p> 

### Click OpenVpn

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161561762-777be237-ccc3-45a5-9df5-8500f46eda69.png">
</p> 

### Download VPN

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161561916-87f6fd74-b246-4c24-99c5-c8a6d18573ac.png">
</p> 

### Go to Downloads -> Open terminal here -> sudo openvpn (downloaded file name.ovpn)

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161562203-d80966ed-7fcc-4ec9-9b16-f6994084f7b8.png">
</p>

### Vpn Connected

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161563110-feb7219e-e1c9-40f0-a49b-d83c16dd5036.png">
</p> 

----------------------------------------------------------------------------------------------------------------

## Step-2 Spwan Machine

### Click Spawn Machine button 

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161563287-1f07f287-4a57-4fa9-aa22-ff8d6a2d2116.png">
</p> 

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161985434-3f413cad-9e63-42c1-b538-ec11980c9b8c.png">
</p> 

---------------------------------------------------------------------------------------------------------------

## Step-3 Submit the flags

### Task-1

What does the 3-letter acronym SMB stand for?

- Answer: server message block

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161985897-669aaf24-2cc7-4614-a226-9523f6ad5150.png">
</p>

### Task-2 

What port does SMB use to operate at?

- Answer: 445

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161986340-1704f57e-5645-42d1-ba85-85b6d5cd591d.png">
</p>

### Task-3 

What network communication model does SMB use, architecturally speaking?

- Answer: client-server model

### Task-4 

What is the service name for port 445 that came up in our nmap scan?

- Answer: microsoft-ds

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161986915-b02e1ed4-b6ff-4e7f-8e0c-4e7ce32d6e60.png">
</p>

### Task-5 

What is the tool we use to connect to SMB shares from our Linux distribution?

- Answer: smbclient

### Task-6

What is the `flag` or `switch` we can use with the SMB tool to `list` the contents of the share?

- Answer: -L

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161987782-d6ea7d2f-7edc-470b-b809-001c058bd85b.png">
</p>

### Task-7 

What is the name of the share we are able to access in the end?

- Answer: workshares

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161988046-5b1c1882-0877-4d08-9a06-58ea716e7a0b.png">
</p>

### Task-8

What is the command we can use within the SMB shell to download the files we find?

- Answer: get

### Sumbit Root Flag

- Answer: 5f61c10dffbc77a704d76016a22f1664

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161989291-28f0bb7d-1cff-43d2-8b88-2fa4c26012b2.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161990327-652ccf73-988f-4616-85c4-99a26b61c200.png">
</p>  

-------------------------------------------------------------------------------------------------

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161990000-5c4d3605-1192-4da4-868a-210dec2b1399.png">
</p>  

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/161990530-41b87a69-1f45-471c-be0a-99ef6793cc73.png">
</p>  


-----------------------------------------------------------------------------------------------
