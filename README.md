NewFAT32Sorter 
==============

Sorts Files on FAT, FAT32 devices, with GUI, easy to use

==============
16.02.2014
Built a windows-only and experimental "sort button". Experimental, because a timer waits till windows moves a file by cmd commands and it's possible, that the time is to short. But it works on my PC.

- Added "About" for Apache Commons license

==============
04.02.2014

So, it turns out, that there is a little problem to build a "fast-sorting" funtion with a file-moving function. It seems that windows controls the moving process and sorts the files as usual in a confusing way.

So far, copying all files is the only solution to create a sorted file order.



==============
11.01.2014


Right now, the application copies files from one direction to another. The user 
decides in which order the files are copied, what leads to a sorted order on a 
regular FAT32 drive.


 - Copies files in a given order
 - File extension filter
 - Copies only new files
 - File dates (creation, accessed, modified) are copied to the new files if possible
 - Subfolders included
 - Saves most user input in a text file

==============

System requirements:
 - Java 7

==============

Built with Net Beans, tested in Microsoft Windows 7. 
Using Apache Commons IO to copy and move files.

==============

Start the application:
 - Download and extract the repository
 - Start application with clicking "NewFAT32Sorter.jar" with mouse
 
==============
 
 
 ToDo's:
  - Show Output in real-time
  - make better code (error messages, ...)
  - Work on GUI 
  - Implement "Fast Sorting" (Move files, instead of copying them)
  - User defined exclusion of folders
 
==============
 
 Stefan Sax
