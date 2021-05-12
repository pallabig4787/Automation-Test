# Automation-Test

# Application to Be tested:
  lightweight to-do list webapp
  
# Features:
  The application is a simple To-Do list app which can be used both as a desktop or mobile app. It can be used to make a checklist of tasks. 
  Once the task is completed, it can be striked out or completely deleted. 
  
# Test Scenarios:
  Positive
  1. User should be able to insert a task in the application
    Expected: Once user types a task and hits enter a task is created in the app
  2. User should be able to strike out the tasks that are completed.
    Expected: Clicking on the radio button on the left hand side of a task should strike it out.
  3. User should be able to delete the completed and striked out tasks
    Expected: Clicking on 'Clear Completed' should delete the completed task.
  4. User should be able to edit any task.
    Expected: Double clicking any task should enable edit functionality.
    
   Negative:
   1. User should not be able to edit any completed and striked out task.
      Expected: Completed and Striked Out task should not be editable when double clicked.
   2. User should not be able to add duplicate tasks
      Expected: A warning message when a duplicate task is created.
   3. User should be restricted on the number of characters allowed in a row.
      Expected: Validation on the number of charaters in a row
   4. User should be restricted on the number of tasks that can be added on the app
      Expected: Validation on the number of taks created.
      
 # Automation using SeleniumIDE:
 
 Steps to 



