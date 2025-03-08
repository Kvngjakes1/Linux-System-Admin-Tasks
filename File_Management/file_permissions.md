# Linux File Permissions & Ownership Management

## Task: Modify File Permissions & Ownership

### Steps Performed:
1. Created a directory `project_files` and added files inside it.
2. Changed ownership of the directory and files to `newuser`.
3. Set different permission levels for the files.

### Commands Used:
```bash
mkdir /home/newuser/project_files
cd ~/project-files
touch file1.txt,file2.txt,script.sh
sudo chown -R jakes:jakes /home/jakes/project_files
chmod 644 /home/newuser/project_files/file1.txt
chmod 600 /home/newuser/project_files/file2.txt
chmod 755 /home/newuser/project_files/script.sh
ls -l /home/newuser/project_files

Challenges:
Initially, I got a "Permission denied" error when changing ownership. Fixed by using sudo.

Observations:
The ownership change worked correctly.
Permission changes reflected as expected.
![file-permission1](https://github.com/user-attachments/assets/52177e65-0685-4d78-83b5-e5684fa7ecbd)

![file-permission2](https://github.com/user-attachments/assets/ba9f709d-d3dd-45ba-90c5-6bee24bdc9c8)


