Question 1:

Descending sort(Alphabetical):


ls -lr


or


ls -r



Descending sort(by Time):


ls -lt


or


ls -t



Descending sort(by Size):


ls -S -l


or


ls --sort=size -l

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Question 2:


syntax: rar a new_rar.rar test

This will create an archive file name "new_rar" for the directory "test"

setting password:

syntax: rar a –p new_rar.rar

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Question 3:

syntax: zip new_zip_file.zip test.txt

This will create an zip file name "new_zip_file" for the "test.txt"

setting password:

syntax: zip -e new_zip_file.zip

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Question 4:

{{{You can place cursor on specific line and column at startup}}}

syntax: nano +line,column file_name

Ex: nano +6,3 Test.txt

as soon as file opened, cursor is at the sixth line and third column.



{{{You can backup a file before the file get edited.}}}

syntax: nano -B file_name

The backuped file will be saved in the current directory with the same filename but suffixed with a tilde (~).


Tip:
the point is the files that you creat for first time can't be backuped.


{{{You can use tab instead of space button}}}

syntax:  nano -E file_name

according to title,the tabs were converted into spaces.

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++








