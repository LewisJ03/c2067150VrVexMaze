Author: Lewis James(c2067150)

Built with: Python(vr.vex specific library)

Github:https://github.com/LewisJ03/c2067150VrVexMaze

Video:https://youtu.be/xrmA3WgUR0M

Run instructions:
-open:https://vr.vex.com/
-go to file, open, select file .vrpython file

Overview:
This is a project in which a robot must travel through a maze in the fastest way possible. While doing this the robot must not miss any turnings which it may pass.
To accomplish this I have designed a program which follows Dijkstra's algorithm comparing each path and following the shortest out of the possible options. This
allows for me to treat each turning as a node and the distance(mm) in-between turnings can then be thought of as weights for these node. Doing this also allows
for the maze to be mapped as it is traversed and if a node is visited twice it can be counted as untraversable and therefore any paths which may lead to dead ends
can be cut off.


What I have learnt:
This project has taught me a great deal about implementing Dijkstra's algorithm into practical code and has taught me many valuable lessons about collision physics
