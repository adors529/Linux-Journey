Section 2 — File and Folder Operations

## mkdir
It is used to create a new directory

**Example**
mkdir NewDirectory

## mkdir -p
This comand is used to create a full tree structure or nestad directories at once

**Example:**
mkdir -p Subjects/Maths/Marks/Sem1/SectionA

## touch
touch command is used to create file witout opening it

**Example**
touch index.html

## cp 
It is a command for file management, allowing you to create exact copies while keeping the original file intact.

**Example**
cp File1 File2


## cp -r
this command is use to copy files and directories from one location to another.

**Example**
cp file.txt new_file.txt

## mv
mv command is used to move or rename files and directories

**Example:**
mv file1_name.txt new_file_name.txt



## rm 
rm command is used to remove file or directory permenently

**Example:**
rm file1.txt

## Flags
-i Interactive : Prompts you for confirmation before deleting each file
-f Force: Deletes files without asking for confirmation, even if they are write-protected
-rf Recursive force :it will permanently erase the file and all its content without permission
**Example**
rm -i file1.txt
rm -rf file1.txt
rm -f file2.txt


## cat
cat command is used to read the content inside the file and it is also used to conctinate the files

**Example**
cat New_file.sh

cat New_file.sh New_file2.sh

## less
less command is used a terminal pager used to view the contents of a text file or command output one screen at a time.

**example** 
less Newfile.txt

## more 
The more command in Linux is a terminal utility used to view the contents of a text file one screen (or page) at a time.

**flags:**
-d: Provides helpful navigation prompts instead of just a bell sound for errors.
-n (or -number): Specifies the number of lines to show per screen (e.g., more -10 file.txt).


## head
 Outputs the beginning section (first 10 lines by default) of a specified file

**Example**
head syslog.txt displays the first 10 log entries.

## head -n
Outputs a specific, custom number of lines from the beginning of a file.

**Example**
head -n 5 config.cfg ,displays only the first 5 configuration lines.

## tail 
Outputs the final section (last 10 lines by default) of a specified file.

**Example**
tail error.log , views the 10 most recent error entries.

## tail -f
Monitors a file in real-time, appending new lines to the screen as the file grows.

**Example** tail -f server, log tracks live incoming application traffic.

## nano
Opens an easy-to-use, command-line text editor to create or modify files directly in the terminal.

**Example** nano script.sh ,opens the shell script file for live editing.

## wc -l
Counts and displays the total number of newline characters (lines) inside a file.

**Example**
wc -l users.csv ,shows how many user rows exist in the database export.

## wc -c
Counts and displays the total number of bytes (character count) contained in a file.

**Example** wc -c readme.md outputs the exact file size metric in bytes.