# Djikstra-Implementation
Point and rigid robot

                                        ENPM661    Project 2 : - Djikstra Implementation . 
Group :- Divyam Garg and Preyash Parikh

Nodes are explored by djikstra's algorithm and backtracking was applied with same giving the most optimal path and avoiding the obstacles.

User inputs :-  
first co-ordinante of start node
second co-ordinate of start node
first co-ordinate of goal node
second co-ordinate of goal node

Point robot:- 
Action space of (300*200) = (Length, Breadth) with obstacles within the action space and no clearance given  
of start node or goal node is in the obstacle the statement ("start/goal in the obstacle is mentioned"). 


Rigid robot:- 
Clearance of 'c' is given with the added clearance of radius of robot (r) making it total of r+c
r and c are prefixed to 2 but can be changed and taken as user input by uncommenting line 36 and 37 
and commenting line 40 and 41
       
