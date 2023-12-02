# **To-Do List Project**

## **Overview**

This is a simple To-Do List coding project designed to help you organize your tasks efficiently. The project is implemented in Python, and it provides a basic command-line interface for managing your to-do items.

## **Features**

- Add tasks with a title.
- View a list of all tasks.
- Mark tasks as completed.
- Remove tasks from the list.
- Show a report of how many tasks are completed and uncompleted


## **Getting Started**

### **Prerequisites**

Make sure you have Python installed on your machine.

### **Installation**
1. Clone the Repository

   `git clone https://github.com/joshli0/todolist.git`
   
5. Navigate to the project directory

   `cd todolist`
  
3. Run the application

   `todo.py`
   
## **Usage**
### **Adding a Task**

To add a new task, use the following command:

`todo.py add "Title"`

Replace "Task Title" with the title of your task

### **Viewing Tasks**

To view tasks, use the following command:

`todo.py ls`

### **Marking a Task as Completed**

To mark a task as completed, use the following command:

`todo.py done [NUMBER]`

Replace [NUMBER] with the number of the task you want to mark as completed.

### **Removing a Task**

To remove a task, use the following command:

`todo.py del [NUMBER]`

Replace [NUMBER] with the number of the task you want to delete.

### **Showing a Report**

To show a report, use the following command:

`todo.py report`

### **Show the List of Commands**

To show the list of commands, use the following report:

`todo.py help`

### File Storage

Completed tasks and uncompleted tasks are saved to files named todo.txt and done.txt, respectively, for persistent storage. These files are automatically created and updated as you add, complete, or remove tasks.
