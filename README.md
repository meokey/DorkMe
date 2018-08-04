# DorkMe
<a href="https://asciinema.org/a/XT6U3c9XqwSNN4vTetxssc0e9" target="_blank"><img src="https://asciinema.org/a/XT6U3c9XqwSNN4vTetxssc0e9.png" /></a>

# Dependencies
     pip install -r requirements.txt
It is highly recommended to add more dorks for an effective search, keep reading to see how

# Usage

python DorkMe.py --help

example:python DorkMe.py --url target.com --dorks vulns -v (recommended for test)

python DorkMe.py --url target.com --dorks Deprecated,Info -v (multiple dorks)

python DorkMe.py --url target.com --dorks all -v (test all)


# About
DorkMe is a tool designed with the purpose of making easier the searching of vulnerabilities with Google Dorks, such as SQL Injection vulnerabilities.

Any idea, failure etc please report to telegram: blueudp

dork folder contains -> dorks to search, result folder contains -> results of DorkMe execution

Tested in ParrotOS
# Beta Version
Remember DorkMe is beta, to avoid bans DorkMe wait about 1 minute on each request and 3 minutes every 100 requests

# Add Dorks 

If you want to add new dorks put it in one of the files in the dorks folder (preferable in its category), if it is not, you can add it to mydorks.txt.
    to add it: in the first line add the dork, in the second the severity: high , medium or low, and finally its description, look at the other files to do it correctly
    
EXAMPLE:

    inurl:php?id= [enter]
    
    high [enter]
    
    SQLi [enter]
    
    (space)
    
    another dork
    
    
# Contact Me
Telegram: blueudp
Twitter: https://twitter.com/blueudp
