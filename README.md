# Bash-Commands
``su`` - temporarily become the superuser
</br>
``sudo`` - temporarily become the superuser
</br>
## Change file ownership from 'me' to 'you' 
``chown you some_file``
</br>
## Change group ownership
``chgrp new_group some file``
</br>
## Change access rights
``rwx rwx rwx = 111 111 111 (111 in binary is 7)``
</br>
``rw- rw- rw- = 110 110 110 (110 in binary is 6; 101 in binary is 5)``
</br>
``rwx --- --- = 111 000 000 (100 in binary is 4)``
</br>
``chmod 600 some_file``
</br>
## Count the number of lines in a text file
``wc -l sample_text_file.txt``
</br>
## Count the number of words in a text file
``wc -m sample_text_file.txt``
</br>
## Count the number of files in a folder/directory
``ls -l <folder> | wc -l``
 </br>
 ## Looking at the first few lines of a text file
 ``head -n 2 sample_text_file.txt``
 </br>
 ## Print the working directory 
 ``pwd``
 </br>
 ## Get the PATH variable (https://unix.stackexchange.com/questions/111550/what-is-path-on-a-mac-os)
 ``echo $PATH``
 </br>
 ## Add to the PATH variable 
 ``nano ~/.bash_profile``
 </br>
 ``export PATH=$PATH:/Library/PostgreSQL/12/bin`` (append this at the end of the .bash_profile and save the changes made)
 </br>
 /Library/PostgreSQL/12/bin is the path where I want my system to look for the executables.
 </br>
 ``source ~/.bash_profile`` (Type this in the terminal. This will force the .bash_profile to execute and \ load the values immediately)
 </br>
 ``echo $PATH`` (confirm if the changes have been made)
 
 

