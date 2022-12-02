0x01. Shell, permissions
0. 
1. 
2. #groups :- script that prints all the groups the current user is part of
3. #chown betty hello :- script that changes the owner of the file hello to the user betty
4. #touch hello :- script that creates an empty file called hello
5. #chmod u+x hello :- script that adds execute permission to the owner of the file hello
6. #chmod 754 hello :- Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
7. #chmod ugo+x :- script that adds execution permission to the owner, the group owner and the other users, to the file hello
8. #chmod 007 heloo :- script that sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissions
9. #chmod 753 hello :- Write a script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10. #chmod --reference=olleh hello :- script that sets the mode of the file hello the same as olleh’s mode. The file hello will be in the working directory The file olleh will be in the working directory 
