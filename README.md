Project 2: FTP Client

High Level Approach:

First, I get the input from the user in command line.  Then depending on how many arguments are given, I assign the arguments.
I set messages that would be static to variables for code convenience.  I then parsed the url to retrieve the necessary information to complete the protocol (username, hostname, etc.) . I then use a sream of commands to the server to set up the environment needed for the project.  The program sends a command, parses the recieved message, and acts differently depending on if the url was provided first or second for some commands.  Mv, cp and rm all act quite similarly in this way.  To finish the program a quit commandis sent to the server, closing the connection.

Challenges:  Overall, this assignment wasn't too challenging for me, but something I found difficult was definitely testing the code, as we were not speifically given any unit tests.  How I tested my code is covered in the next section, but creating the debug messages in the correct spots to figure out where my code was messing up was difficult.A major challenge I faced was 

Testing:

Testing my program was difficult, however I mainly did so by placing print messages throughout the program as I went.  I normally would print things like the server output statements, variables to make sure they were the correct values, etc.  I removed these debug statements from the code as they were mostly unnecessary for the final code.  I also tested my code by seperately running each command manually
