========================
BUILD OUTPUT DESCRIPTION
========================

Right now, the application copies files from one direction to another. The user 
decides in which order the files are copied, what leads to a sorted order on a 
regular FAT32 drive.


System requirements:
 -Java 7

 
Built and tested in Microsoft Windows 7, with NetBeans 


Start the application:
- Download and extract the repository
- Start project with clicking "Projekt1.jar" with mouse or in console 
java -jar "Projekt1.jar" 
 
 
 ============================================================================
When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "Projekt1.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
