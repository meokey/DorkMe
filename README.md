# DorkMe
<a href="https://asciinema.org/a/XT6U3c9XqwSNN4vTetxssc0e9" target="_blank"><img src="https://asciinema.org/a/XT6U3c9XqwSNN4vTetxssc0e9.png" /></a>

# dependencies
     pip install google
     pip install argparse
It is highly recommended to add more dorks for an effective search, keep reading to see how

# use
python DorkMe.py --help
example:python DorkMe.py --url bible-history.com --dorks vulns -v (recommended for test)
python DorkMe.py --url bible-history.com --dorks Deprecated,Info -v (multiple dorks)
python DorkMe.py --url bible-history.com --dorks all -v (test all)

# about
DorkMe is a tool designed by blueudp with the purpose of accelerating the search of vulnerabilities with google.

Any idea, failure etc please report to tg: blueudp

dork folder contains dorks to search, result folder contains results of DorkMe execution
# is beta!
Remember dorkme is beta,to avoid bans dorkme wait about 1 minute on each request and 3 minutes every 100 requests

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
