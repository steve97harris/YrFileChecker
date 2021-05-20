Instructions:

1. Launch the app by double clicking YRContentChecker inside the Project folder.

2. Locate and open the settings file inside StreamingAssets; Project\YRContentChecker_Data\StreamingAssets.

3. Set the ContentMatrixPath to the location of your content matrix. (Must have .csv at the end).

4. Set the ContentFolderPath to the location of your content folder. 

5. Set the FileNameHeader. (This is the column header for the list of file names in the content matrix).

6. Click either the 'Check Folder' or 'Check Matrix' button. 

Functions:
CheckFolder;
This gets a list of all the file names specified in the content matrix, 
adds _prn and _scr to the name and then checks these files are located in the content folder.
If a scr or prn file is not found in the content folder the extension type will be displayed in red. 

Check Matrix;
This gets a list of all png files in the content folder that have _prn in the name. 
Then checks the content matrix to make sure this file is named in the content matrix.
If a file is not found in the content matrix it will list the file in the scroll view.