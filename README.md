Hello,

This repository contain two methods delete_last_line and sum_of_bytes.
Both methods can be called by the command line. The first step is downloading my code. Than go in to your terminal and find the directory this assignment is in. To execute the methods run:

 ./delete_last_line

 ./sum_of_bytes

*******************************************************************************


1. The first command (./delete_last_line) deletes the last lines of files that start with BZ_ or  end on .txt. The command is recursive. In all the files, where the last line should be deleted I added the following sentence: *******This line should be deleted********
By checking the files before and after running the command you can see if the method did is job.
In case you made it a git project by running the command <git diff> you can easily see what changed.

  Some thoughts I had by writing the code:
    - Does not store temporaly the file. If command of file is interupted, chance of last of old file can occur

2. The second command (./sum_of_bytes) return the sum of the bytes of all the files in the current directory that have an 'e' in their file name.

  Some thoughts I had by writing the code:
    - Doesnot include files with capitalized E.


*************************************************************************************
