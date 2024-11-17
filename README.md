java c
ENG 335 Computational Intelligence
2024
ASSIGNMENT 3
Genetic AlgorithmsThis is a compulsory assessment item. It counts 15% towards the final assessment and contributes to learning outcome ILO7.  ILO7 is assessed in this assignment and a mark of 50% is required to achieve this ILO.
Goals:
Develop a genetic algorithm for optimising the location of an emergency response unit in order to minimise the response time to a medical emergency in a city.
Submission Requirements:
This assignment is for a group of two students. Each group submits a single report (should include the User’s Guide) as well as software developed.
Plagiarism:
Each assignment must be entirely your own work.   Plagiarism  is  not  tolerated  (you will automatically fail the course).
Problem description:
Part 1
The city is mapped into a 7 km × 7 km grid, shown in Figure 1.  A number in each sector of the grid represents an average number of emergencies per year in a given sector.

Figure 1.  A grid-map of a 7 km × 7 km city.
A fitness function can be defined as a reciprocal of the sum of distances weighted by emergency rates:where λn is the emergency rate in sector n;  (xn, yn ) are the coordinates of the centre of sector n; and  (xeru, yeru ) are the  location coordinates of the  emergency response unit.  It  can be assumed that the emergency response unit can be located only in the centre of a sector.
Part 2Devel代 写ENG 335 Computational Intelligence 2024 ASSIGNMENT 3
代做程序编程语言op a genetic algorithm for the problem described in Part 1 assuming that there is a river that divides the city into two parts, West and East, atx = 5 km.  West and East are connected by abridge located atx = 5 km andy = 5.5 km, as shown in Figure 2.

Figure 2.  A grid-map of a 7 km × 7 km city divided by a river.
Find the optimal location of the emergency response unit and compare it with the one obtained in Part 1.
Guidelines:
This assignment should take about 8 hours of work.  Remembering that a report is required, you should aim to allocate your efforts in roughly the following proportions:
1.         Familiarisation with the travelling salesman problem            10%.
2.         Implementation of the genetic algorithm                                50%.
3.         Testing the genetic algorithm                                                  10%.
4.         Developing a user-friendly interface (GUI)
with simulation of the algorithm                                            20%.
5.         Assignment Report                                                                  10%.
Assignment report should include the following:
1.         Introduction.
2.         Short description of the domain problem.
4.         Description of the genetic algorithm developed (examples are required!).
5.         User’s Guide.
6.         Conclusions.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
