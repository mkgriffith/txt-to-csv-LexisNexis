# txt-to-csv-LexisNexis
Takes a downloaded plain text LexisNexis file and converts it into a CSV file.


The original code (split_ln.py) was created by Neal Caren on 2012-05-14 
[neal.caren@unc.edu]

The original script, while successful on Mac computers, threw up an error on my PC - - "ZeroDivisionError: float division by zero". Due to the type of error, the issue was likely with the code rather than the data. T

The original script's code for line endings needed to be changed for the code to run on my Windows machine. We replaced "/r/n" with "/n" throughout. 

The new code (pcsplit_ln.py) now works on my PC. 

pcsplit_ln.py was adapted for PC by Alex Rudy and Melissa Griffith on 2015-12-06