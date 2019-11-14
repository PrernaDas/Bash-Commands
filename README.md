# Bash-Commands
**su** - temporarily become the superuser
</br>
**sudo** - temporarily become the superuser
</br>
## Change file ownership from 'me' to 'you' 
**chown you some_file** 
</br>
## Change group ownership
**chgrp new_group some file** 
</br>
## Change access rights
rwx rwx rwx = 111 111 111 (111 in binary is 7)
</br>
rw- rw- rw- = 110 110 110 (110 in binary is 6; 101 in binary is 5)
</br>
rwx --- --- = 111 000 000 (100 in binary is 4)
</br>
**chmod 600 some_file**
</br>
## Count the number of lines in a text file
wc -l sample_text_file.txt 
</br>
## Count the number of words in a text file
wc -m sample_text_file.txt
</br>
## Count the number of files in a folder/directory
ls -l <folder> | wc -l
 </br>
 ## Looking at the first few lines of a text file
 head -n 2 sample_text_file.txt
 </br>
 ## Get the working directory (`print the working directory`)
 ``pwd``
 
 

