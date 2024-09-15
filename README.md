# Calendar
Calendar / ToDo app made in Godot using C#. <br />
Currently uses local SQLite database with Entity Framework Core for saving notes. <br />

ToDo panel showing individual and recurring tasks
![alt text](https://github.com/kiwinir/Calendar/blob/main/img/ToDoPanel.png?raw=true)

Panel with advanced settings where choosen options create a recurring rule.
![alt text](https://github.com/kiwinir/Calendar/blob/main/img/AddingNewRecurringNote.png?raw=true)

Calendar tiles view showing in green days where % of task marked as done was greater than 50%, in red below 50%, in darker color days that aren't part of this month.
![alt text](https://github.com/kiwinir/Calendar/blob/main/img/CalendarPanel.png?raw=true)

Different panels can be shown at the same time
![alt text](https://github.com/kiwinir/Calendar/blob/main/img/ToDoPanelAndCalendarTilesPanel.png?raw=true)

Planned things:<br />
	- Other types of notes : Events, goals, simple notes.<br />
	- A way to create groups of notes, allowing to filter and sort by groups.<br />
	- Editing notes (currently only deleting is possible).<br />
	- Calendar panel view with time on the side, which would allow to put events and task on particular date and time on Calendar. <br />
	- Create a server that could be used as a database, allowing multiple devices to synchronize notes. <br />
	- Allow offline mode, and synchronization of data when device becomes online. <br />
	- Importing events and tasks from other popular services. <br />