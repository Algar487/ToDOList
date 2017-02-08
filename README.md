# ToDOList
TO DO List application in android
The app is a simple todo app that can add new todos and delete those that you have completed.
The app makes use of SQLite Database.
The app is working fit and fine on my samsung GT-s7562 which is api level 15

<strong>Activities</strrong>
MainActivity
TaskContract and TaskDbHelper inside the db folder

MainActivity consists of following main functions:
  OnCreate() which is overridden at project creation by the studio
  OnCreateOptionsMenu() we should write this method and then let studio override
    This is used to create the menu. res>menu>main_menu.xml 
    The function takes an instance of Menu as a parameter.
  onOptionsItemSelected()
    This function handles what is to be done when the Add icon not the button is clicked.
   
   Other important functions are updateUI() which updates the xml on invoking and the deleteTask() which deletes a record and also calls the updateUI() within it.
   

TaskContract class defines constants which are used to access the data in the database
Helper class--> TaskDbHelper is nedded to open the database

The code also consists of comments to help you understand better
