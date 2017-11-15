# ToDOList
TO DO List application in android<br>
The app is a simple todo app that can add new todos and delete those that you have completed.<br>
The app makes use of SQLite Database.<br>
The app is working fit and fine on my samsung GT-s7562 which is api level 15<br>

#### Single Activity:
`MainActivity`<br>
<strong>Other two classes:</strong>
`TaskContract` and `TaskDbHelper` inside the `db` folder<br>
<br>

### `MainActivity` consists of following main functions:<br>
<ul>
<li>`OnCreate()` which is overridden at project creation by the studio</li>
<li>`OnCreateOptionsMenu()`.<br>
    This is used to create the `menu`. `res>menu>main_menu.xml` <br>
    The function takes an instance of Menu as a parameter.</li>
<li>  `onOptionsItemSelected()`<br>
    This function handles what is to be done when the Add icon is clicked.</li>
    </ul>
   
<br>   Other important functions are `updateUI()` which updates the xml on invoking and the `deleteTask()` which deletes a record and also calls the `updateUI()` within it.<br>
   

`TaskContract` class defines constants which are used to access the data in the database<br>
Helper class--> `TaskDbHelper` is nedded to open the database<br>
<br>

The code also consists of comments to help you understand better.
