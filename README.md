# ToDOList
TO DO List application in android<br>
The app is a simple todo app that can add new todos and delete those that you have completed.<br>
The app makes use of SQLite Database.<br>
The app is working fit and fine on my samsung GT-s7562 which is api level 15<br>


### To test:
* Clone the repository using `git clone` or download the zip.
* Open the project in Android Studio, build and run.

<strong>Single Activity:</strong> `MainActivity`
<strong>Other two classes:</strong>
`TaskContract` and `TaskDbHelper` inside the `db` folder<br>
<br>

#### MainActivity consists of following methods:
* `OnCreate()` which is overridden at project creation by the studio</li>
* `OnCreateOptionsMenu()`. This is used to create the `menu`. `res>menu>main_menu.xml` <br>
    The method takes an instance of Menu as a parameter.</li>
* `onOptionsItemSelected()`. This method handles what is to be done when the Add icon is clicked.
* Other important methods are `updateUI()` which updates the xml on invoking and the `deleteTask()` which deletes a record and also calls the `updateUI()` within it.
   

`TaskContract` class defines constants which are used to access the data in the database<br>
The helper class `TaskDbHelper` is nedded to open the database<br>
<br>

> The code is commented.
