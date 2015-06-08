WorldCruncher v0.1
-----
This is a very early version of the WorldCruncher. It only reads in files for industrial sectors and nations and runs some basic checks. Only very limited number crunching actually happens at this stage.

Nations are only accepted if no conflicts with the rules are found. Some warnings are also given about stats that are unusual but admissable. I plan to put these rules in a file in the future but for now they are hardcoded.

Sectors don't do anything right now but the idea behind them is hopefully straightforward. For anyone's whose played Supreme Ruler it will look extra familiar.

Files for sectors and nations must follow the exact format as provided. Which file anything is in is purely for human oversight. The program reds all in the relevant directory. Multiple nations and sectors can be in one file, but make sure not to have whitespaces at the end.
-----
Checks:
- Percentages for workforce, unemployment, etc. lower than 100
- Armed forces size relative to population lower than 5% and active troops lower than total