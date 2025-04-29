# Using-tools-like-John-the-Ripper-for-password-cracking
## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).


### Step 3:
Use John the Ripper to crack the hashes:

## PROGRAM:
Password Cracking with John the Ripper

## OUTPUT:
- Create an txt file
  
![435691224-e7328b13-1938-444d-bb77-6be3377f430e](https://github.com/user-attachments/assets/c19396c1-6b54-4ac3-8e4a-e19f47a2d346)

- Create a Password-Protected ZIP File

  ![435691479-46f87c52-2b2c-48a3-916f-aaaa53cc687d](https://github.com/user-attachments/assets/1064b4f7-8a2a-48b6-ad42-6241ee6d4bc0)


## OR
```
zip -e secret.zip file.txt
```
- Open John-The-Ripper Tool

![435692837-fae39a60-9f20-474e-b7a1-9132d5d1d88a](https://github.com/user-attachments/assets/0fe80e83-888c-492a-ad71-dd8607da3930)

![436909316-7a69d91f-a92c-4b5d-86ec-99fa6682c2b1](https://github.com/user-attachments/assets/ed061e06-74ea-41df-95c0-40335284bab9)


 - ## Generate Hash Using zip2john

![435700815-2a9a53f8-f51e-462c-979e-6d346b720280](https://github.com/user-attachments/assets/17bde191-7169-483c-ba80-bf20801d26e8)

- ## cat hash.txt

![435700732-18aa5639-556a-4a63-b983-7e6d674aac6b](https://github.com/user-attachments/assets/f74eb1d5-4111-423e-aace-85a5e80cc616)

![435702649-10c4fe4f-e04d-4d44-829d-036cf0d7f34f](https://github.com/user-attachments/assets/1a733c0a-11fb-41b0-a83b-00899ae29df1)


## RESULT:
The password hashes were successfully cracked using John the Ripper.

