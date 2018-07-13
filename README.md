# DorkMe
<a href="https://asciinema.org/a/XT6U3c9XqwSNN4vTetxssc0e9" target="_blank"><img src="https://asciinema.org/a/XT6U3c9XqwSNN4vTetxssc0e9.png" /></a>
# dependencies
     pip install google
     pip install argparse
use: python DorkMe.py --help
example::python DorkMe.py --url bible-history.com --dorks vulns -v 

DorkMe is a tool designed by blueudp with the purpose of accelerating the search of vulnerabilities with google.

Remember that dorkme is beta, is full of errors, and is not yet optimized for use

Any idea, failure etc please report to tg: blueudp

dork folder contains dorks to search, result folder contains results of DorkMe execution

to avoid ban, between each request there are between 50 and 65 seconds, and between every 100 requests from 3 to 4 minutes
# add dorks 
if you want to add new dorks put it in one of the files in the dorks folder (preferable in its category), if it is not, you can add it to mydorks.txt.
    to add it: in the first line the dork, in the second the severity, high , medium or low, and finally its description, look at the other files to do it correctly
EXAMPLE:
    inurl:php?id= [enter]
    high [enter]
    SQLi [enter]
    (space)
    another dork
# contact me
Telegram: blueudp
twitter: https://twitter.com/blueudp
