# Translation-Tool-
To run the project from the command line, go to the dist folder and
type the following:

java -jar "Translate.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* If the classpath contains a folder of classes or resources, none of the
classpath elements are copied to the dist folder.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

If you need any information. Please contact me by Email: cksnaidu@gmail.com
