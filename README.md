# LibreOffice Sheet
The document currently works for 40 people and 8 hanchan (some provisions for 44 people are made).
Simply enter the player names in the "Number Assignments" sheet.

# Solver
We used [LocalSolver](http://www.localsolver.com) in order to generate the seating.
The provided cpp file is mostly based on their social golfer example with the extra condition that every player should have every position exactly twice.
The position on the table corresponds to the wind.

Please follow the steps in [https://www.localsolver.com/documentation/exampletour/socialgolfer.html](the example) to get this working on your platform.
Be aware that you will have to obtain a license to use LocalSolver (there are free academic and trial licenses).
