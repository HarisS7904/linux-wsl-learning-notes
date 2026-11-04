# Permissions of files or folders
to know what permission the files have we can run this command:
```bash
ls -l
ls -la  # if want to include hidden files
```
expected output:
```text
-rw-r--r-- user user timestamp FILE
|  |  |  |_permission for everyone else
|  |  |____permission for users in the file group
|  |_______permission for owner
|__________ '-' = ordinary file/ 'd' = directory
```
r = read
w = write
x = execute

can change permission using chmod:
```bash
chmod [ugoa][+-][rwx] FILE # add or remove the permission of specified file
```
# Delete files
Before every deletion run these command:
```bash
pwd
ls
```
Then type the files to delete.
Never use rm -r or rm -rf without checking
```bash
rm -r # recursively include folders's content
rm -f # force the command ignoring the warning
```
