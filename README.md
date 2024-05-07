# Tasks

How to use?
==================
Via script: `bash install.sh`

This will generate the binary and set up the database. If you want, you can copy the binary and the public folder into a folder of your choice.

Manually:
1. change dir to the respective folder and create the db file: `cat schema.sql | sqlite3 tasks.db`
1. run `go build`
1. `./Tasks`
1. open [localhost:8081](http://localhost:8081)

## Features

1. Add, update, delete task.
2. Search tasks, the query is highlighted in the search results page.
3. Github flavoured markdown, which enables us for using a task list, advanced syntax highlighting and much more.
4. Supports file upload, randomizes the file name, stores the user given filename in a db and works on the randomized file name for security reasons.
5. Priorities are assigned, High = 3, medium = 2 and low = 1, sorting is done on priority descending and created date ascending.
6. Categories are supported, you can add tasks to different categories. 
1. Ability to hide a task from the timeline.
1. For a task list, shows 6 out of 8 tasks completed.





# Screenshots
The Home Page

![Home Page](https://github.com/thewhitetulip/Tasks/blob/master/screenshots/FrontEnd.png)

Add Task dialog

![Add Task](https://github.com/thewhitetulip/Tasks/blob/master/screenshots/FrontEnd-Add%20task.png)

Navigation drawer

![Navigation Drawer](https://github.com/thewhitetulip/Tasks/blob/master/screenshots/FrontEnd%20Navigation%20Drawer.png)


