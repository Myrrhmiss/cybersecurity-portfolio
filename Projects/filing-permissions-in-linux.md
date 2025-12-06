## File Permissions in Linux

#Description of the Project

I work at an organization that needs to update the file permissions for specific files and directories. These are found within the projects directory. The permissions do not reflect the level of authorization. As an analyst is my job to verify and update these permissions to secure their system. In order to fulfill my task, I did the following:

#Check file and directory details

Please review the following codes used to determine the existing permissions for a specific directory.

![file-permissions-in-linus-Evidence 1](../images/my-image.png)

The command I entered will show on the first line. The rest of the lines display the output, presenting the content of the “projects” directory. First, I used “ls -la” to display a detailed list of the file content. This command displayed hidden files, indicating one directory named “drafts”, one hidden file named “.project_x.txt” in addition to five project files. The permissions set on each file is presented as a ten character string in the first column.

# Describe the permissions string

In order to determine who is authorized to access the file and their specific permissions can be deconstructed as follows:

First Character: is either a “d” or hyphen (-), it indicates the file type.

- If the character is a “d”, then is a directory
- If the character is a hyphen (-), then is a regular file.
 
Second-Forth Characters: these indicate the read (r), write (w) and execute (x) permissions for the user. 

- If one of these characters is a hyphen (-), then it indicates the permission is not granted for that user.

Fifth-Seventh Characters: it indicates the read (r), write (w), and execute (x) permits for the group.

- If one of these characters is a hyphen (-), it means the group does not have permission.
- 
Eight-Tenth Characters: they indicate the read (r), write (w) and execute (x) permissions for other users apart from the user and the group.

- If this character is a hyphen (-), then it means that “other users on the system” don’t have permission.

# Change File Permissions

Our agency stated that other users shouldn’t have “write” access to any files. In order to comply with this request, I went back to the previous permissions and stated that the “write” access from “project_k.txt” for other users, should be removed.

This is the code that shows how I used the Linux commands to fulfill this task:

![file-permissions-in-linus-Evidence 2 Pt1](../images/my-image.png)

![file-permissions-in-linus-Evidence 2 Pt2](../images/my-image.png)

The commands I entered are displayed on the first two lines, the output display the output of the second command entered. The “chmod” command changes the permissions on files, and directories. The first task indicates the permissions that should be changed, and the second states the specific file or directory. Here the “write” permissions have been removed from “other” for the “project_k.txt file”. Once this step was completed, I used “ls -la” to review the updated information.

# Change File Permissions on a Hidden file

My team archived “project_x.txt” and in addition to this, they won’t want anyone with “write” access to the project. However, the “user” and “group” should have “read” access. 

This is the code I used to change permissions:

![file-permissions-in-linus-Evidence 3](../images/my-image.png)

The commands I entered are displayed on the first tow lines ad the other lines show the output of the second command. The period (.) on “.project_x.txt” clearly states is a hidden file. 
Removed “write” permissions from the “user” with “u-w” and group with “g-w”
Then, I added “read” permissions to the “group” with “g+r”.

# Change Directory permissions

My agency requested that only researcher2 user to have the access needed for the drafts directory.

This image shows the Linux commands I used in order to change directory permissions:

![file-permissions-in-linus-Evidence 4](../images/my-image.png)  

The commands entered are displayed on the first two lines. The rest of the lines display the output of the second command entered With the “chmod” command I removed the “execute” permits granted to the “group”. There was no need to add the execute permission for user researcher2 as he already had it.

Now the multiple permissions match the required level authorized by my organization for files and directories within “projects”. In order to proceed, I used “ls -la” to check the permissions for the directory. Then, I used the chmod command, in order to change the permissions on the files and directories.
