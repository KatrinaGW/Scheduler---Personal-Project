CONTENTS OF THIS FILE

* Introduction

* Requirements

* Included Files

* Running Instructions

* Notes


INTRODUCTION

Scheduler.py is a current work in process project, meant to generate a weekly schedule for employees' who work in shifts. 

REQUIREMENTS

The following files MUST be contained in the same directory when running the program:
* dictGenerator.py
* Person.py
* scheduler.py (This is the main file)
* TextProcessor.py
* Any text files used as input to the scheduler

INCLUDED FILES

* dictGenerator.py
* Person.py
* TextProcessor.py
* scheduler.py
* testInput
* testInputTwo


RUNNING INSTRUCTIONS

* Currently, this program can only be run from the command line. To run the program, use the command: python3 scheduler.py
* When prompted, enter an input file name, two test input files are included in this repository. 
* If the input files do not contain settings for the schedule, the user will be prompted for this information on the command line. Note that all but the skipdays responses will be case sensitive. 
* The weekly schedule, along with warnings about unfilled positions, will be printed to the standard output

NOTES:
* Plans for future functionality include: multiple shifts of varying lengths, wages and payroll, optional overtime. 
