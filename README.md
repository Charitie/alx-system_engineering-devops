# alx-system_engineering-devops
How shell permissions work.

**usermod** A command that changes your user ID.

**id -u** A command that prints the numeric user id of the current user.

**groups** A command that prints all the groups the current user is part of.

**chown** A command that changes the owner of the file.

**touch** A command to create a new empty file. 

**chmod u+x** A command that adds execute permission to the owner of the file.

**chmod ug+x,o+r** A command adds file execute permission to the owner and the group owner, and read permission to other users.

**chmod a+x** A command that adds execution permission to the owner, the group owner and the other users for a file.

**chmod ug=,o=rwx** A command that sets all permissions to other user and no permissions to user and groups.

**chmod 1113** A command to set file permissions as **-rwxr-x-wx-**.

**chmod a=r,ug=w** A command to set file permissions as **-rw-rw-r--**.

_chmod -R a+x dir*_ A command used to change permissions to subdirectories **dir**  only.

**mkdir -m 751 dir_holberton** A command to create directory **"dir_holberton"** with permissions 751.

**chgrp** A command to change file group ownership.

**chown [OPTIONS] USER[:GROUP] FILE(s)** A command to change both Owner and group name.





