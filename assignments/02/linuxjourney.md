1.
$ date
Wed Oct 23 17:26:35     2024

$ whoami
jbuse

Q: What should be outputted to the display when you type echo Hello World?

A: Hello World


2.
No exercises for this lesson


Q: How do I find what directory you are currently in?

A: pwd


3.
Run the cd command without any flags, where does it take you?

back to the top level instance: jbuse@Jab-Book MINGW64 ~

Q:If you are in /home/pete/Pictures and wanted to go to /home/pete, what’s a good shortcut to use?

A: cd ..

4.
Run ls with different flags and see the output you receive.

ls -R: recursively list directory contents
$ ls -R
.:
notes.txt

ls -r: reverse order while sorting
$ ls -r
notes.txt

ls -t: sort by modification time, newest first
$ ls -t
notes.txt


Q: What command would you use to see hidden files?

A: ls -a

5.
Create a new file
$ touch newfile.txt

Note the timestamp
$ ls -l
total 1
-rw-r--r-- 1 jbuse 197609  0 Oct 23 17:50 newfile.txt

Touch the file and check the timestamp once again
$ touch newfile.txt |  ls -l
total 1
-rw-r--r-- 1 jbuse 197609  0 Oct 23 17:53 newfile.txt

Q: How do you create a file called myfile?
A: touch myfile

6. 
