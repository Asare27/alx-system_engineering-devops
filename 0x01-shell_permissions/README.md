su betty -Create a script that switches the current user to the user betty
whoami -script that prints the effective username of the current user.
id -nG - script that prints all the groups the current user is part of.
touch -script that creates an empty file called hello
chmod - -reference=olleh hello -script that sets the mode of the file hello the same as olleh’s mode
chown betty hello - Changes the file owner to betty
chmond u+x hell0 -script that adds execute permission to the owner of the file hello
chmod ug+x,0+r hello script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod ugo+x hello script that adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello -script that sets the permission to the file hello as follows Owner: no permission at all Group: no permission at all,Other users: all the permissions
chmod 753 hello -script that sets the mode of the file hello to this:The file hello will be in the working directory,You are not allowed to use commas for this script
mkdir -m 751 mydir -script that creates a directory called mydir with permissions 751 in the working directory.
chgrp school hello -script that changes the group owner to school for the file hello
