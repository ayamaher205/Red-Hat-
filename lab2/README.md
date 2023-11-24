## lab Two
### 1. Create a user account with the following attribute
#### username: islam
#### Fullname/comment: Islam Askar
#### Password: islam
####
##
![Q1-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/0fb4a4bb-cc21-4127-913b-d34a45a00500)
##
### 1. Create a user account with the following attribute
#### username: baduser
#### Fullname/comment: Bad User
#### Password: baduser
####
##
####
![Q2-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/5374632c-a0d4-4ec0-a119-87cb1e9d356e)
#### 
##
### 3.Create a supplementary (Secondary) group called pgroup with group ID of 30000
#### ![Q3-2-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/7c2c2ddd-6d22-4674-9832-b8386253e8ee)

##### 
#####     
##
### 4. Create a supplementary group called badgroup:
##
![Q4-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/247f73df-c10b-4d2d-becd-18ff8af9eada)

####
##

### 5. Add islam user to the pgroup group as a supplementary group:
####
##
####

![Q5-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/52f073c9-99db-42fc-9fd7-e2075f0ddb17)

##
### 6. Modify the password of islam's account to password:
##
####
![Q6-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/6c562be9-ec58-4218-a1d5-b6d64cedd80b)
##

### 7. Modify islam's account so the password expires after 30 days:
##
####

![Q7-2-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/67a1a60c-dbab-4018-a3b9-90981951857c)
##
### 8. Lock bad user account so he can't log in:
####
##
![Q8-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/ddfc6b19-e94d-4e06-9f5a-a52dc20efbe9)
##
### 9. Delete bad user account:
##
![Q9-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/8d9a44af-bcb3-484f-b929-c8f6ae738ded)
##
### 10.Delete the supplementary group called badgroup.
##
![Q10-2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/a2cb95aa-fbea-447d-99d1-55e6c111bf40)
##
### 13. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
##
![13](https://github.com/ayamaher205/Red-Hat-/assets/79773094/47e67c50-fe91-4868-b3de-6a3d4720cf18)
##
### 14. Log out and log in by another user
##
![14](https://github.com/ayamaher205/Red-Hat-/assets/79773094/86f0b743-69c3-4c38-9ed5-7be4a4e900f6)

##
### 15. Try to access (by cd command) the folder (myteam)
![15](https://github.com/ayamaher205/Red-Hat-/assets/79773094/c071b720-9a15-4540-aa07-e150d6324e49)
##
## 16. Using the command Line 
#### a. Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute 
#### and execute only for the others (using chmod in 2 differen
##
![16,1](https://github.com/ayamaher205/Red-Hat-/assets/79773094/155b8d3e-ffce-42e7-936f-dbb82352038d)

![16,2](https://github.com/ayamaher205/Red-Hat-/assets/79773094/7049d167-4b27-450f-a69b-2ff6be495a83)
##
## b. Change your default permissions to be as above.
##
![16,3](https://github.com/ayamaher205/Red-Hat-/assets/79773094/87d2a143-bdd5-49eb-bd28-7b46cbfdf103)
##
## c. What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
##
##### for file >>> the maximum is two and those two permissions are read and write 
#### for directory >>> the maximum is three and those three permissions are read, write and excute 
##
## d. Change your default permissions to be no permission to everyone then create a directory and a file to verify.
##
![16,4](https://github.com/ayamaher205/Red-Hat-/assets/79773094/6df65f46-4097-4642-a9c2-ba05a65cead3)
##
## 17.What are the minimum permission needed for:
### a. Copy a directory (permission for source directory and permissions for target parent directory)
#### for source directory >>> read only
#### for target directory >>> excute and write to add file in directory
### b. Copy a file (permission for source file and and permission for target parent directory)
#### for source file >>> read only
#### for target directory >>> excute and write to add file in directory
### c. Delete a file
#### file >>> don't need any permissions 
#### directory >>> excute and write
### d. Change to a directory >>> excute and write 
### e. List a directory content (ls command) >>> read only
### f. View a file content (more/cat command) >>> read only
### g. Modify a file content >>>> read and write
##
## 18. Create a file with permission 444. Try to edit in it and to remove it? Note whathappened.
![18,1](https://github.com/ayamaher205/Red-Hat-/assets/79773094/7ca436ae-4730-4159-9005-0c6795715557)
##
![18](https://github.com/ayamaher205/Red-Hat-/assets/79773094/4a60cf3b-770e-4853-a836-9ba6ce7cf2f6)
##
## 19. What is the difference between the “x” permission for a file and for a directory?
#### for directory means >> be able to enter inside it by command cd 
#### for file means >> to be able to run it
##




