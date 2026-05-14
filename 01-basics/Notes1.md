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

