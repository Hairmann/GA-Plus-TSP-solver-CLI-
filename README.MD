# GA Plus
This project is a Travelling Salesman Problem (TSP) solver, that uses Genetic Algorithms (GA) to find optimal solutions. Some new ideas, such as route untwisting was implemented to make the algorithm more efficient.
Folder "Sea Ports Genetic" should be inserted into My Documents folder.
"input.csv" file contains main inputs on sea ports, i.e. their names, x coordinates, y coordinates.
"matrix.csv" is used to store data on distances between sea ports.
"modes.csv" contains setup options for the algorithm:
     nSteps - the number of steps, performed by the algorithm;
     printStepRate - indicates % of steps, results of which are being displayed in CLI, while running the algorithm;
     percentMutation - % of solutions being mutated on each step;
     isModeMin - boolean, if [T] the algorithm tries to find minimal solution; if [F] the algorithm tries to find maximal solution;
     isUntwistOn - boolean, if [T] the untwisting subfunction is performed;
     isCraftedOn - boolean, if {T} the nearest neighbour subfunction is performed.
"results.csv" is used for saving the results of the algorithm run.
This version of the genetic algorithm for TSP is the most efficient and most robust so far.

To run the app: MyDocuments\Sea Ports Genetic\GAplus\GA_plus.exe