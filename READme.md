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

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQL Injection (SQLi)

Description: The salesperson info is vulnerable to SQL injection. You can inject certain codes in the URL and it will wait 7 seconds before processing the request.

<img src="https://github.com/Krishna-Oli/Web-Application/blob/main/blue-vuln1.gif">

## Green

Vulnerability #1: Username Enumeration

Description: Typing correct username but wrong password, you get an error. After the inspecting you find out
that the error is spanned by class="faliure". When an incorrect username is used, error returns class="failed".

<img src="https://github.com/Krishna-Oli/Web-Application/blob/main/green-vuln2.gif">


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)

Description: Viewing the salesperson info you can put ?id=10 or ?id=11 to view hidden information.

<img src="https://github.com/Krishna-Oli/Web-Application/blob/main/red-vuln1.gif">



## Notes

Describe any challenges encountered while doing the work
