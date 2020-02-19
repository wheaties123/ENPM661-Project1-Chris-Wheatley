Chris Wheatley
University of Maryland (College Park)
ENPM661 Spring 2020
Dr. Monfaredi
Project #1

Project Description:
This program will provide the optimal path plan for a blank tile in the tradional 8-piece slider game, for any solvable starting configuration.

The project contains the following files: 
	-project1_main_wheatley.m
	-BlankTileLocation.m
	-solvabilityCheck.m
	-ActionMoveRight.m
	-ActionMoveLeft.m
	-ActionMoveUp.m
	-ActionMoveDown.m

Please see comments at the top of each .m file for descriptions of what each function does.

User Instructions:
1) Ensure that MATLAB is installed on your machine (2015b or later).

2) Download all project contents and unzip the "proj1_chris_wheatley.zip" contents into a newly created local directory.

3) In MATLAB, change the working directory to the working directory created in step #2.

4) Run the "project1_main_wheatley.m" script from the working directory created in step #2.

5) A prompt will appear to solicit user input.  It says "Enter the starting node configuration (use brackets an semi-colons to define a 3x3 matrix):". Type a valid 3x3 matrix, using backetets and semicolons to separate rows, and then type "Enter".  
   Example Input: [1 8 2; 0 4 3; 7 6 5]
   
7) Once the program has finished running, one of two outcomes will occur:
   1) A statement will be printed out to the screen saying "Input tile configuration is not solvable." if the user-specified input node is not solvable.
   2) Three output text files will appear in the directory created in step #2:
		-Nodes.txt
		-NodesInfo.txt
		-nodePath.txt
