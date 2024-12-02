### su01 : User Maintenance initial screen.
![image](https://github.com/user-attachments/assets/3904086a-7dbf-440f-87a6-0af9407dfa4e)
Below are the logos in su01 screen:
- Create
- Edit
- View
- Delete
- Copy User : Apart from address data, remaining all details can be copied.
  - ![image](https://github.com/user-attachments/assets/1a394199-f177-443c-aea0-56d5288423b7)
  - While copying, Last name will be automatically populated with username.
- Lock : To lock the user
  -  ![image](https://github.com/user-attachments/assets/2309e2b2-2a57-4aec-9df2-20b550d85814)
  -  To know reason why the user is locked, check Change documents under, Information --> Change Documents
    - ![image](https://github.com/user-attachments/assets/90412729-b12b-41cf-9c4d-1c6d71ae7c7b)
    - ![image](https://github.com/user-attachments/assets/a34a5964-2e00-4d9d-a202-e58df9098391)
    - ![image](https://github.com/user-attachments/assets/4fbca218-1f4c-4b5d-b3f9-e5a62186cc31)
  - Before unlocking, check the reason for locking the user. We can know using Return codes.
     - 0 : Not locked
     - 64 : Admin Lock
     - 128 : Incorrect Passowrd lock
     - 32 : CUA lock (Central User Administration). If user is locked in CUA system, then it will be locked in all other systems, showing 32 code.
