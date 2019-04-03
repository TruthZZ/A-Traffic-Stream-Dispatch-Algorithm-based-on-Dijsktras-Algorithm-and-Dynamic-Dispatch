# A-Traffic-Stream-Dispatch-Algorithm-based-on-Dijsktras-Algorithm-and-Dynamic-Dispatch
A Python implementation of Dijkstra's Algorithm for finding short routes and develop a traffic schedule in certai traffic network.

Competant in Huawei Codecraft 2019
the program is consistst of 2 parts:
1. The implementation of Dijkstra's Algorithm, whivh is used to find the shortest route for all the cars. The core part of this algorithm is the class FindSRoute.
2. Three classes of the Cars, Roads and Crosses, and one Class IterateDispatch for dynamic dispatch and arrange the most efficient traffic time schedule, as well as changing the route of cars when the roads is fully occupied.

Four .txt files are the example of the parameters:
1. Three input files: car.txt road.txt and cross.txt are the input information of the traffic networt and the cars planning to depart.
2. One output file: answer.txt include the planned departing time and the planned route for each car.

To run the program, use this command in Linux environment: “python CodeCraft-2019.py ../config/car.txt ../config/road.txt ../config/cross.txt ../config/answer.txt”
The three input file should be included in folder ../config and the answer.txt will be generated in the same folder.
