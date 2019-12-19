# 52957_Data_Rep_Project_MK
2019 - Repository for the main project of the Data Representation module, Mark Kelly

These files can be run locally. The commands to run create the SQL table and a couple of entries has been included in the 
text file 'SQL_CREATE_DB.txt'.
The 'dbconfigtemplate.py' would need to be renamed as dbconfig.py with the local user settings. The server is then run using the 
'set FLASK_APP=application.py' and then 'flask run' command and the main html page is the localhost/patientViewer.html 
or http://127.0.0.1:5000/patientViewer.html. 

Entries into the database can be inputted and updated/deleted via the webpage. 
The SQL database can be checked to verify that the commands are working correctly by using 'select * from patientinfo;'

This project is also available on pythonanywhere. 

The pythonanywhere page where the files are stored are located here..
https://www.pythonanywhere.com/user/MarkKelly/

Andrewbeatty1 has been made a Teacher so has access to all of the files and server. 
It may be required to restart the server upon viewing this.
This is done in the following steps:
  Select Dashboard for https://www.pythonanywhere.com/user/MarkKelly/
  Under 'All Web apps' select the link 'MarkKelly.pythonanywhere.com'
  Select the reload button - 'Reload MarkKelly.pythonanywhere.com'
This should restart the server if necessary
  
The html page can be found here..
http://markkelly.pythonanywhere.com/patientViewer.html.

If there are any issues loading or using the database or pythonanywhere, please contact me at G00364705@gmit.ie
