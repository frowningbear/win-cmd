# win-cmd
Windows Command Line notes

to go back a directory



cd ..



go back 2 directories



cd ../..



to autocomplete (Desktop folder for example)



cd D



then hit tab on keyboard



and woila! cd Desktop



press tab multiple times to cycle through other folders starting with the letter D



to list folders and files



dir



to list another directory without changing your working directory



dir Desktop\Some Folder



to show hidden directories as well



dir /a



to clear screen



cls



to list files by type



dir *.jpg



for multiples



dir *.jpg,*.txt



or



dir *.jpg *.txt



to go through cmd history



press the up arrow for back and down arrow for forward



to open a file in default app just type its name



Use quotes for files with spaces



to access help for a command



ipconfig /?  



to create a directory



mkdir FolderName



to delete a directory



rmdir FolderName



to delete a non-empty folder



rmdir /s Foldername



to navigate back and forth on a command faster thanusing left and right arrows, use home key and end key 



to navigate left and right by a word at a time, hold ctrl + left or right 



to cd to an absolute path



cd C:\Files\css



when using tab to cycle through directories, windows will automatically add quotes to directory names containing a spaces



cd "C:\Program Files"



to see path variable



path



toview list of drives



wmic logicaldisk get name



to switch drives just type in the drive letter followed by a colon



to show a directory structure



tree



to change colors



color 0B



to retore to default (07) just type



color



to create a file with some text



echo some text > myfile.txt



to view files and their attributes



attrib



to add an attribute to a file



attribute +h bacon.txt (h or some othe rattribute)



add an attribute and remove one at the same time



attrib +r -h bacon.txt



to delete a file



del filename.txt



to read a text file in the command line



type filename.txt



to append to a file instead of overwriting



echo new text >> bacon.txt



to output command results to a file

dir > myfile.txt



to copy a file



copy srcfile.txt Testfolder



copy srcfile.txt E:



to copy all files from one directory to another



xcopy sourcefolder destfolder



to copy all files and sub-directories from one directory to another



xcopy sourcefolder destfolder /s



to move a file or directory into another directory



move sourcething destfolder



to rename a directory



rename oldname newname































.
