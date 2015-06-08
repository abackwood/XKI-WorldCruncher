WorldCruncher v0.1
-----
This is a very early version of the WorldCruncher. It only reads in files for industrial sectors and nations and runs some basic checks. Only very limited number crunching actually happens at this stage.

Nations are only accepted if no conflicts with the rules are found. Some warnings are also given about stats that are unusual but admissable. I plan to put these rules in a file in the future but for now they are hardcoded.
-----
Checks:
- Percentages for workforce, unemployment, etc. lower than 100
- Armed forces size relative to population lower than 5% and active troops lower than total