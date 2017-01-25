##Some Common UNIX commands

**who am i** - displays the current user and the time at which user logged in.

**pwd** - shell displays the present working directory.

**cal** `<month> <year>` - displays the calendar.
	cal monthNo year (example '$ cal 7 1995' or '$ cal feb 1995' will dispay the calendar of july 1995).

**date** - displays the current date, __date__ '+Date:%y-%m%nTime:%H-%M-%S' will display date in custom format.

**mkdir** `<directorName>` - create directory.

**ls** - list files in present working directory.

**cd** `<directoryName>` - change directory.

**touch** `<fileName>` - creates an empty text file in that directory.

**cat** > `<fileName>` - creates a file, press clt+D to close the file.

**cat** < `<fileName>` - reads the file.

**cat** `<file1>` `<file2>` > `<destinationFile>` - merges file1 and file2 into destination file.

**rm** `<fileName>` - deletes the file.

**rm - r** `<directoryName>` - deletes the directory.

**mv** `<fileName>` `<newFileName>` - changes the fileName to newFileName.

**ln** `<file1>` `<file2>` - establishes a hard link between file1 and file2.

**ln -s** `<file1>` `<file2>` - establishes a soft link between file1 and file2, soft link is just a pointer, file2 points to file2.

**ls -l** - displays files and folders along with permissions. 

**ls -l** - displays all files including hidden files.

**chmod** `<currentUser>` `<groupOfcurrentUser>` `<others>` `<filename>` - 4 for read, 2 for write, 1 for execute, ex - chmod 754 file, this gives all permission to user, read and execute permission to group and only read permission to other users.

**wc** `<fileName>` - lists the no of lines, words and characters in ASCII text files, -l for lines, -w for words and -c for characters.

**sort** `<filename>` - sorts the lines in the file in alphabetical order and displays on the screen.

**cut** -d"`<delimiting character>`" -f `<columnNo>` - extracts columns from data in tabular form.