# Python-Getting-the-contents-of-a-Directory
Enumerate the files in the output folder.

In wordprocess.py, delete the placeholder print statement in line 133, and enter the code as shown.


Line 134 initializes the counter i to use in the loop.
Line 135 iterates through each item in the directory listing.
Line 136 prints the name of the item, using the counter i as an index to access the item from the list.
Line 137 increments the counter.
Test the program to get the current directory's contents.

In the Project pane, right-click wordcount.py and select Run 'wordcount'.

At the first prompt, enter bartleby.txt

Because you provide no path, the manuscript file will be read from the current directory (the project folder).

At each of the remaining prompts, enter y.

Verify that the program has listed the contents of the Wordcount Output folder.


In various test runs of the program, you have analyzed two different manuscripts, and their results are stored in the output folder.
Note that if you were to run another analysis of open-boat.txt or bartleby.txt, the new log file would overwrite the old one.
