# Create a Directory
command:
```bash
pwd   # show your starting folder or current location
ls    # list visible files and folder available in current location
mkdir # "make directory" make a folder with name be explicit
cd    # move shell current location into the destination
```
# File Making and Editing
command:
```bash
touch  # create an empty file if it does not exist or update timestamp if exist
ls -la # list contents with detail listing and include hidden files
nano   # text editor, will open text editor for the files mentioned
cat    # prints a text file to the terminal
```
# Redirection
command:
```bash
echo "" >  # echo prints the words after it. > create/overwrites the destination files
echo "" >> # >> will append the words at the end line of files
```
# Copy, Move and Rename
command:
```bash
cp SRC DEST # copy file from source to destination
mv SRC DEST # move file from source to destination or rename file
rm FILE     # remove a file
```
# Command guide
command:
```bash
ls --help   # prints a quick built-in guide
man COMMAND # opens a longer manual of that command
```
# Search
command:
```bash
find . -name "NAME"  # find all files that matching the search conditions 
grep -n "TEXT" FILE # find matching text inside specified file
```
