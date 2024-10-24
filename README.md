#Group Members:
- Shruti Jayavardhanan
- Jacob Malin
- Romeo Sweeney
- Nathan Kjaer


# Project 1 Overview
This project is a culmination of the skills and knowledge acquired in C++ programming and the Waterfall methodology throughout the course of the semester in csci 5801 Software Engineering. The project focuses on development and waterfall development methodologies. The objective is to create a voting system capable
of performing two algorithms: closed party listing (CPL) and open party listing (OPL).

## Description
Our group coded our project using the software requirements specification (SRS) document and software design
document (SDD) we made to guide us. We completed our own unit testing and provided documentation of these unit tests as
part of the deliverables. In addition, we ran run tests to ensure the program as a complete system is working and that
the software requirements have been fully meet (i.e., integration and system testing). Since the operation and
maintenance phase is the phase that occurs only after the system has been put into practical use, we will only document
the issues and bugs that have not been fully fixed that would be fixed as part of the operation and maintenance phase.

# Project 2 Overview
Some new changes made to the system and new functionalities were added. Instead of using the traditional Waterfall methodology to complete the new changes and functionality, we now used the Agile Scrum to do one 2-week sprint. Shana, the product owner for the system has put together an initial description of what the election officials and others would
like to see in the improved software.
Improvements in the software:
- The CPL and OPL algorithms work fully as described in project #1. (Each bug that was not fixed will in Project 1 became e a user story that will became a PBI.)
- Added another type of voting algorithm. This algorithm determines multiple winners based on the candidates receiving the most ballots with a fair coin toss if there is a tie or ties between candidates. This algorithm is called Multiple Popularity Only (MPO).
 There can be 1 to many seats to fill. There will always be enough candidates to fill the seats.
- The MPO election ballots are brought in via as a .csv file so the election can run.
- The MPO stats displayed to the screen at the end of the election so that people know who
won and who lost. Displays the percentage of votes each candidate received so that constituents know how well their candidate did in the election. Make clear who won seats and who did not.
- Added feaure to allow in multiple files instead of a single file.
- Added another type of voting algorithm. This one determines multiple winners based on the candidates receiving the most ballots with a fair coin toss if there is a tie or ties between candidates. A voter is allowed to
pick from 1 to the number of candidates. This algorithm is called municipal voting (MV).
- Added a featureto allow MV election ballots to be brought in via as a .csv file so the election can run.
- MV stats displayed to the screen at the end of the election so that people know who won and who lost. They can know number of votes received by all of the voters.
