# codepathweek8
codepathweek8assignment
# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: _____SQLI_____________
The id field in the find a salesperson page allows for sql injection in the ID field. The other two pages bring you back to the list page. 

Vulnerability #2: _____Session Highjacking/Fixation_____________
The blue site allowed me to login as the administrator when I copied the PHP session id to edge from chrome. The red and green sites prevented this. 


## Green

Vulnerability #1: ____Username Enumeration______________
On the login page, the developer used a different error class for an incorrect password and for an incorrect user name. 

Vulnerability #2: _______XSS___________
the feedback page on the green page allows for cross site scripting attacks. Both the name field and the feedback field are vulnerable. 
 



## Red

Vulnerability #1: ____IDOR______________
On the find a salesperson page the developer does not check if the page is public when the get request is made. This allows the user to access any id.
 


Vulnerability #2: _____Cross Site Request Forgery_____________



## Notes

Describe any challenges encountered while doing the work

