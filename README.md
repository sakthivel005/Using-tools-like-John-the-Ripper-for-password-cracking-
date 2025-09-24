# Using-tools-like-John-the-Ripper-for-password-cracking
### Name : Sakthivel R
### Reg.No : 212222100044
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
  
![txt file](https://github.com/user-attachments/assets/9ad6e3cf-cb6f-49a4-93ae-b0ee5b191e72)


- Create a Password-Protected ZIP File

  ![zip text file](https://github.com/user-attachments/assets/a2034a1e-1801-456c-bb1a-a079d482d7c4)



## OR
```
zip -e secret.zip file.txt
```
- Open John-The-Ripper Tool

![john tool](https://github.com/user-attachments/assets/5643249e-7f58-4556-89ab-09ae83dd93d0)


![john helper](https://github.com/user-attachments/assets/d726ea74-f67e-4114-9f69-f20d0f0e6350)



 - ## Generate Hash Using zip2john


![zip2john](https://github.com/user-attachments/assets/76deaacc-964d-48c4-8a8b-a70ce2fa0ce6)



![hash text](https://github.com/user-attachments/assets/12b5bb49-cff9-428c-b056-3a4ea640cfac)





- ##  hash.txt

![john format](https://github.com/user-attachments/assets/f44872fa-7e68-43be-88d5-1483120dab77)


![john show](https://github.com/user-attachments/assets/7c13fc7f-b681-4e14-ac4f-5da4035555f9)



## RESULT:
The password hashes were successfully cracked using John the Ripper.
