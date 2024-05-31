# instal vim editor
```
atul@atul-Lenovo-G570:~/mydjangofirst/derp$ sudo apt install vim
```
check the url for more: https://www.guru99.com/the-vi-editor.html 

# show files and directory
1. see hidden and non hidden directory and files
   ```
   atul@atul-Lenovo-G570:~/fprofile$ ls -la

   ```
2. see only hidden files
   ```
      atul@atul-Lenovo-G570:~/fprofile$ ls -a
   ```

3. see only non hiden files and directory
   ```
      atul@atul-Lenovo-G570:~/fprofile$ ls -l
   ```

# delete all directory and files from current directory
```
:/var/www/fprofile$ rm -r ./*
```
-Note1: It does not delete hidden files
-Note2: . – The current directory indicated by a single dot.
-Note3: .. – The parent directory indicated by two successive dots.


# delete all hidden files
```
:/var/www/fprofile$ rm -r ./.*
```
