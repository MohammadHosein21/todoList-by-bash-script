# todoList-by-bash-script
A todo list is written with bash script for Linux where you can add a task to it, search for the task in it, show the tasks as a list, add the tasks to the done state and cleared the task list.

To add a task to the list of tasks, we use the add command, which has two options -t (--title) and -p (--priority). The first option is for job title and the second option is for job priority. Entering title is mandatory and entering priority is optional.
If the title is not entered, the message "Option -t|--title Needs a Parameter" will be displayed.
The priority takes three values L(Low), M(Medium) and H(High) as input and its default value is L. If values other than those are entered, the message "Option -p|--priority Only Accept L|M|H" will show.(add)

To clear the list of tasks, we use the clear command.(clear)

We use the list command to display the available tasks.(list)

To find the desired task, we use the find command, which takes the title of the task as an input.(find)

To change the task to completed, we use the done command, which takes the task number shown in the list as input.(done)



