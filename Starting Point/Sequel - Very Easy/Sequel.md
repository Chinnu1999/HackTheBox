# SEQUEL - VERY EASY
----------------------------------------------------------------------------------------------------------------

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/161996471-1f2b6a38-1947-4c7f-93bc-2bb8d23b9868.png">
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/162229102-bb8667d4-fbed-440d-844d-3ce1241b7023.png">
</p>

----------------------

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
 <img src="https://user-images.githubusercontent.com/94435318/162229442-a5245c66-2274-452d-a576-a6b462963426.png">
</p> 

---------------------------------------------------------------------------------------------------------------

## Step-3 Submit the flags

### Task-1 

What does the acronym SQL stand for? 
- Answer: Structured Query Language

### Task-2

During our scan, which port running mysql do we find? 
- Answer: 3306

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162230006-73d16cc9-9c45-46d0-9632-aea8aef3ae1b.png">
</p>

### Task-3

What community-developed MySQL version is the target running? 
- Answer: MariaDB

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162230341-b7153982-623c-40e0-852c-ead58efd42d2.png">
</p>

### Task-4 

What switch do we need to use in order to specify a login username for the MySQL service? 
- Answer: -u

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162230793-dc274e0c-776d-431c-90e0-53c1c634df42.png">
</p>

### Task-5

Which username allows us to log into MariaDB without providing a password? 
- Answer: root

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162231223-3054d7ec-b43f-4a2a-bd92-4a7ee2f69ca9.png">
</p>

### Task-6 

What symbol can we use to specify within the query that we want to display eveything inside a table? 
- Answer: *

### Task-7

What symbol do we need to end each query with? 
- Answer: **;**

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162231781-d546e6cf-7633-4bfc-af96-781c7c5f4730.png">
</p>

### Task-8

Submit Root Flag
- Answer: 7b4bec00d1a39e3dd4e021ec3d915da8

      mysql -u root -h 10.129.228.111
      show database;
      use htb;
      show tables;
      select * from users;
      
<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162232056-98b539c9-3cbc-49ab-8dcb-1fadbc6054f6.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162232311-dd31009a-a6c5-4145-ae4d-8a820f91d5e2.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/94435318/162232428-e255648c-0087-44fd-bcf8-df7567264346.png">
</p>

---------------------------------------------------------------------------------------------

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/162233241-20d1f35c-a9d8-4519-817c-9cc4f781508d.png">
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/94435318/162233550-423b58c6-281a-4aa1-bb2c-7c6d4c88ed7f.png">
</p>

----------------------------------------------------------------------------------------------




