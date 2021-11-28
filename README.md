# File_management

we all know that to organize all this files indiviually is very hard and time tasking task.

so we going to write a python script that aotomatically orgainzes all this files.

let's start coding....

first's import os and shutil modules. This are inbulit modules,so don't need to stall them.

Then lets create variable name path. Which take input of files path that we have to organizes.

then create variables called files which consist of list of files.

now for loop conditions=os.path. splitetext(file).we only need extention name source slicing

extention=extention[0:]

Then we write a if conditions

if the extentions directory is exist,then we move the files to that directories.

in else statement we make directories that auotomatacally move it.
