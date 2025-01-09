# Linux_File_Permissions

This project includes a directory named robot, which contains a Python file named arm. The command chmod (Change mode) I used to set the file permissions to (-rwxrwxr-x).
__________________________________________________________________
Why Use File Permissions?

File permissions control who can read, write and execute a file(-) or directory(d). These permissions are categorized into three groups:

1. Owner (User): The user who owns the file.
2. Group: A group of users that share the same permissions.
3. Others: All other users.

Each group can have the following permissions:
- Read (r): Allows viewing the contents of the file.
- Write (w): Allows modifying the contents of the file.
- Execute (x): Allows running the file as a program/script.
- No permission (-): No access.

Numeric Values for Each Permission
- Read (r) = 4
- Write (w) = 2
- Execute (x) = 1
- No permission (-) = 0

Examples of permissions:
1. Permission1: drwxr-xr--
- Meaning: We have a directory that the owner can fully control, and the group can read and execute, while other users can only execute it.
- Numeric Score: 754

2. Permission2: -rwx------
- Mean: We have a file that only the owner can fully control, and others have no access.
- Numeric Score: 700
