The source files are compatible with all recent versions of Eclipse. 
Uncompress the file in the proper directory. It contains two '.jar' archives: 'src.jar' and 'resources.jar'.

For Eclipse 22-09:
1. Create a workplace directory and when starting Eclipse, choose it as the current workplace.
2. To create a Java project:
   2.1. Choose 'File/New/Java project'
   2.2. In the field 'Project name:' enter 'ERST'.
   2.3. In the 'JRE' box, choose 'Use an execution environment JRE:' and make sure that
        the Java JDK chosen is installed on your machine.
   2.4. Click 'Next', clear the 'Create module-info.java file' and click 'Finish'.
   
3. Right-click on the directory 'src' and choose 'Import.../Java/Jar file', and after that browse and
   choose the uncompressed 'src.jar'.
4. Right-click on the main directory ('ERST') and choose 'Import.../General/Archive', and after that 
   browse and choose the uncompressed 'resources.jar'.