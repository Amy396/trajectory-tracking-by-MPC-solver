# Optimal control-Vehicle project-Project
The project is to Control the trajectory of a vehicle in an optimal way.


This folder includes:

This folder contains Four folders, each folder for a certain task of the project.
Each folder contains all the functions needed to run the code


To run the code :
To run the codes, inside each folder, open the “Task_(number of task)_main code” and run the code,
Each folder contains all the functions needed to run the code.


For Task_3 and Task_4, because we have used optimal trajectory to do the tracking,
to avoid computing optimal trajectory when we want to do the tracking,
the variable “Compute_optimal” is defined, and the optimal states and inputs are saved.
In order to compute optimal trajectory, put this variable = True,
otherwise uncomment “Saving optimal” part inside the main code of task_3 and tas_4 to use the saved optimal trajectory instead.


To see the animation for task_3 and task_4 set “visu_animation” = True
