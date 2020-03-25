Basic Commands discussed in Covid-19 Open Source Development Program

Command-1 :

Create Directory(Folder):

Syntax: mkdir Directory_Name
Explanation: Creates a directory/folder with the name given in the command
Example: >mkdir OSDCourse

Command-2:

Create a text file:

Syntax: notepad File_name.txt
Explanation: Creates a text file with the name entered in the command
Example: >notepad name.txt
	       >notepad user.txt

Command-3:

change Directory:

Syntax: cd Directory_Name
Explanation: changes the current working directory to the directory mentioned in the command
Example: >cd OSDCourse

>cd .. ==> takes one step/folder back
>cd\   ==> takes the user to root directory
>dir   ==> prints the available directories in the working space

Command-4:

Move Command:

Syntax: move Source_file "Destination_path"
Explanation: This command moves the file in current folder to the destination path mentioned. The 
	           path must be within the ""
Example: move user.txt  "C:\Users\Vishnu\Desktop\OSDCourse"

Command-5:

Search for a file:

Syntax: dir File_name /s /p
Explanation: This command finds for the file and returns. Here 
              s => Start search opration, 
	            p => Pause search operation
Example: dir user.txt /s /p

Command-6:

Rename Command:

Syntax: rename Old_filename New_filename
Explanation: This command renames the file
Example: rename user1.txt user_1.txt

Command-7:

Syntax: tree
Explanation: This command displays the entire file structure in a tree format
Example: tree

Command-7:

echo Command:

Syntax: echo HelloWorld
Explanation: This command just prints whatever comes after the echo
Example: >echo HelloWorld
	       >HelloWorld

Command-8:

Copy Command:

Syntax: copy "Source_path" "Destination_path"
Explanation: This commands copies the entire file from source to destination.
Example: copy user.txt  "C:\Users\Vishnu\Desktop\OSDCourse"

Command-9:

Delete Command:

Syntax: del File_name
Explanation: This command deletes the file
Example: del user.txt

Note: All the commands work for windows
