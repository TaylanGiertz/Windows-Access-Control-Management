# Windows Access Control Management
## This project demonstrates basic access control management tasks within a Windows Virtual Machine (VM), including enabling password complexity requirements, creating users and groups, and setting permissions on files and folders.
### Steps:
1. Enabled Password Complexity Requirements
   - Configured the Windows VM to enforce password complexity, requiring users to create strong passwords.
    ![image](https://github.com/user-attachments/assets/4cbe993c-b5d7-432f-8186-936ffab89b0b)
2. Created users and groups
   - Created multiple user accounts.
   - Established groups and added the relevant users to these groups.
   - Ensured that no new user was granted administrative privileges.
![image](https://github.com/user-attachments/assets/0d25bdf6-c012-4c53-bc3d-1ffb71f4bb96)
3. Testing File and Folder Permissions
   - Created a folder named Security at the root of the C: drive.
   - Inside the Security folder, created a file named SecurityFile.txt.
   - Assigned read-only access to the SecurityFile.txt for all new groups created.
   ![image](https://github.com/user-attachments/assets/772c7ff8-dc6f-480f-8b4a-c3626a236cb3)
