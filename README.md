# Get_Next_Line

* Calling Get_Next_Line in a loop will read the text available on a file descriptor one line at a time until the EOF, and it can manage multiple file descriptor at the same time.

* it return either 1 if a line has been read or 0 if EOF has been reached, and -1 if an error happened.
