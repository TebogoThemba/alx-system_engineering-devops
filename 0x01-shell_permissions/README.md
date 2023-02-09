this is a shell permissions file that will consist of all shell permission scrips
0_iam_betty is a script that switches the current user to the betty user
1-who_am_i script prints the effective username of the current user
2-groups script prints all the groups of the current user that is part of
3-new_owner script changes the owner of the file 'hello' to the user betty
4-empty script creates an empty file called 'hello'
5-execute script adds execute permission to the owner of the file 'hello'...
6-multiple_permissions script adds execute permission to the owner and the group owner, and read permission to other users, to the file 'hello'...
7-everybody script adds execution permission to the owner, the group owner and the other users to the file file 'hello'
8-James_Bond script sets the permission to the file 'hello' for the owner to have no permission at all, group to have no permission at all, but other users would have all the permissions
9-John_Doe script that sets the mode of the file 'hello' to -rwxr-x-wx julien julien 23 sep 14:25 hello
10-mirror_permissions script sets the mode of the file hello, the file will be the same as olleh's mode
11-directories_permissions script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12-directory_permissions script creates a directory called my_dir with permissions 751 in the working directory
13-change_group script that changes the group owner to school for the file hello
100-change_owner_and_group script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
101-symbolic_link_permissions script changes the owner and the group owner of _hello to vincent and staff respectively
102-if_only script changes the owner of the file 'hello' to betty only if it is owned by the user guillaume
103-star_wars script will play the StarWars IV episode in the terminal
