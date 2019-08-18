# Week-9
Pentesting Live Targets

# Project 8

Time spent: **7** hours spent in total

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

Vulnerability #1: Session Hijacking/Fixation
<img src="https://github.com/PalmTreeForest/CodePath_Week_9/blob/master/Blue_Session_Hijacking.gif" width="800">

Vulnerability #2: SQLi
<img src="https://github.com/PalmTreeForest/CodePath_Week_9/blob/master/Blue_SQLi.gif" width="800">

## Green

Vulnerability #1: XSS
<img src="https://github.com/PalmTreeForest/CodePath_Week_9/blob/master/Green_XSS.gif" width="800">

Vulnerability #2: Username Enumeration
<img src="https://github.com/PalmTreeForest/CodePath_Week_9/blob/master/Green_Username_Enumeration.gif" width="800">

## Red

Vulnerability #1: IDOR
<img src="https://github.com/PalmTreeForest/CodePath_Week_9/blob/master/Red_IDOR.gif" width="800">

Vulnerability #2: CSRF
<img src="https://github.com/PalmTreeForest/CodePath_Week_9/blob/master/Red_CSRF.gif" width="800">


## Notes

The most challenging part of this assignment for me was the SQLi vulnerability. While I was quickly able to determine that Blue Globiteck was the vulnerable web application, it took some time before I was able to find an exploit that demonstrated this vulnerability.
