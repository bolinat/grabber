grabber v.0.1
========

bash script that works as a cli command for ssh'ing to a group of servers which are under one dns record, and grab from a file some data needed and write it to a local file.
it receives from the user a few parameters:

1. user name 
2. host name
3. the source file to search
4. the string to grab
5. the destination file to write the grabbes string into
6. delay interval in case you want to run it every n seconds.

usage: grabber <user> <host> <sourcefile> <string> <destfile> <delay>

