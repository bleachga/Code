# MIND MAPPER

### Program that reads a string of text and creates a mind map from it:

1. Specific Commands:

	| Command| Syntax | What it does|
	| -----  |:------:|-----------|
	| Create | "Create" + "name"| Adds a starting box|
	| Add to | "Add" + "name to add" + "to" + "name to add to"| Adds a box to another box|
	| Add description to | "Add description to" + "box name needing description" |Adds a description to a box, pop up menu to type specifics     |
	| Help | "Help" | Shows a display menu that gives common commands | 

2. Other Ideas

	* add functionality to a calendar, todo list, send it text and it reads the text to add to a calendar (google cal APK) 
	* Will highlight part of the text after it recognizes a command and give tips on how to format correctly (kinda like function/class autofill on text editors)

	
## Plan (modifying a bit to string reader)

1. Create an html page using javascript and canvas that constantly reads the text in a menu bar and displays commands

	* Draw - Draw a shape with the following points
		* Put canvas dimensions in the top middle
		* Take in like a function, ex output:  "Draw a shape 2,2 3,4 5,6 7,8" 	
		* displays an 'x' until the input is valid and then displays a check mark and allows the user to hit enter to draw on the canvas

		
2. To Do List That saves for next time and can send you reminders (Canvas turns into a scrollable to do list with buttons)

