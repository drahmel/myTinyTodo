myTinyTodo
==========

myTinyTodo is based on Max Pozdeev's myTinyTodo. Since development is
abbandoned there, a fork is created and further developed.

System requirements
-------------------
* PHP 5.2.0 or greater;
* PHP extensions: php_mysql (MySQL version), php_pdo and php_pdo_sqlite (SQLite version).
Tested browsers:
* Internet Explorer 8
* Firefox v3.6, v4
* Chrome v8
* Opera v10.60, v11
* Safari v5

How to install myTinyTodo
-------------------------
1. Download, unpack and upload to your site. 
2. Run setup.php, select and specify settings of database you prefer.
   For sqlite usage make sure that database file 'db/todolist.db' is writable for webserver/php.
   Then click "Install" to create tables in database. It's recommended to delete this file after installation.
3. To protect your tasks from modification by the others you may specify password in settings.<br>
   By default session files are stored in 'tmp/sessions' directory. Make sure it's writable for webserver/php.
4. Open 'index.php' in your browser to run the application. Then go to settings and specify your time zone.

Update to new version
---------------------
Download, unpack and replace all files excluding directory 'db'.
Run 'setup.php' and upgrade database if required.

How to show completed tasks
---------------------------
Use appropriate command in the tab menu.

How to hide a tab
-----------------
Hold the Ctrl (or Cmd) button and click on the tab.

How to show tasks from all tabs in one list
-------------------------------------------
There is the "Select List" menu to the right of tabs. 
Here you'll find all the tabs you have created. Hidden tabs too. And special tab with all tasks.

How to select the sorting in reverse order
------------------------------------------
You can toggle the order (ascending or descending) by clicking on the sorting menu item once more (see the arrow).
