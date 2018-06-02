# LibreOffice Sheet
The document works for either 40 or 44 people and 8 hanchan.
The document adjusts itself automatically depending on whether or not there is a name for Player 41 in the Number Assignments sheet.

# Solver
We used [LocalSolver](http://www.localsolver.com) in order to generate the seating.
The provided cpp file is mostly based on their social golfer example with the extra condition that every player should have every position exactly twice.
The position on the table corresponds to the wind.

Please follow the steps in [https://www.localsolver.com/documentation/exampletour/socialgolfer.html](the example) to get this working on your platform.
Be aware that you will have to obtain a license to use LocalSolver (there are free academic and trial licenses).
