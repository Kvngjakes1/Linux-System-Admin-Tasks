# Linux User Management Task

## Task: Create a User and Modify Details

### Steps Performed:
1. Created a user and set a password.
2. Changed the user's home directory.
3. Assigned a new shell to the user.
4. Added the user to a specific group.
5. Verified the changes.

### Commands Used:
sudo useradd -m -s /bin/bash test-admin
sudo passwd newuser
sudo usermod -d /home/customhome test-admin
sudo usermod -s /bin/zsh test-admin
sudo usermod -aG admins test-admin
id test-admin
getent passwd test-admin
ls -ld /home/customhome

### Observations:
- The default shell was changed successfully.
- User home directory was modified.
- Group assignment worked as expected.

### Challenges:
- Initially, I encountered an error with user creation due to missing permissions. Fixed by using `sudo`.

![2nd-user-management](https://github.com/user-attachments/assets/f2338475-c119-440f-a350-81cc5cdc4295)

![user-management1](https://github.com/user-attachments/assets/7ed71f5f-7382-4b50-9e4d-e9fe43e0d418)
