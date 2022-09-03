# ToDoList
-View the to-do list
-Prioritizing tasks
-The possibility of announcing the completion of work
-Search jobs
-Delete tasks

*commands:
  .add
  .list
  .find
  .done
  .clear
  
*add options: -t (--title) & -p (--priority)

*priorities :
    -H as High
    -M as Medium 
    -L as Low

*tasks will be saved to "tasks.csv"

*example:
  bash todo1.sh add -t "First Task" -p H
  tasks.csv --> 0,H,"First Task"
