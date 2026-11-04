# Make and Edit file
command:
```bash
touch note.txt
ls -l
```

expected output:
```text
-rw-r--r-- 1 user user timestamp note.txt # output may differ based on user name and timestamp
```

command:
```bash
nano note.txt  # then write "Linux Practice" in the text editor
cat note.txt
```

expected output:
```text
Linux Practice
```

command:
```bash
echo "another line" >> note.txt
cat note.txt
```

expected output:
```text
Linux Practice
another line
```

command:
```bash
echo "new content" > note.txt
cat note.txt
```

expected output:
```text
new content
```


# Copy, Move and Rename
command:
```bash
cp note.txt new-note.txt
ls
```

expected output:
```text
note.txt new-note.txt
```

command:
```bash
mv new-note.txt old-note.txt
ls
```

expected output:
```text
note.txt old-note.txt
```

command:
```bash
rm old-note.txt
ls
```

expected output:
```text
note.txt
```


# Change permission
command:
```bash
chmod u+x note.txt
chmod g+w note.txt
ls -l
```

expected output:
```text
-rwxrw-r-- user user timestamp note.txt
```

command:
```bash
chmod u-x note.txt
chmod g-w note.txt
chmod o-r note.txt
```

expected output:
```text
-rw-r----- user user timestamp note.txt
```

command:
```bash
chmod a=rwx note.txt
```

expected output:
```text
-rwxrwxrwx user user timestamp note.txt
```

