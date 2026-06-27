# Flask-Brute-Force-Detection-Lab

## Overview

This project demonstrates how a brute-force attack works in a safe local environment. I built a Flask login application, simulated a brute-force attack using Python, and analyzed the login activity from a SOC analyst perspective.


## Objective

The objective of this lab was to build a local Flask login application, simulate a brute-force attack using Python, generate authentication logs, and investigate the login activity from a SOC analyst perspective.

## Tools Used

- Python
- Flask
- Requests
- Command Prompt
- Windows 11
- Visual Studio Code
- GitHub

## Lab Setup

I built a local login application using Flask that ran only on my computer. The application accepted a username and password and checked whether the credentials were correct.

I then created a Python script that automatically tested multiple username and password combinations against the login page. Every login attempt was recorded in a log file for later investigation.

## Files

- **app.py** - Flask login application
- **attack.py** - Python brute-force attack script
- **usernames.txt** - List of usernames used during testing
- **testpwlist.txt** - List of passwords used during testing
- **login_attempts.log** - Log file containing successful and failed login attempts

## Skills Demonstrated

- Web application fundamentals
- Authentication concepts
- Brute-force attack simulation
- Python scripting
- Flask web framework
- Log analysis
- Security monitoring
- Incident investigation

## Investigation Findings

During testing, the brute-force script attempted multiple username and password combinations against the local Flask login application.

Most authentication attempts failed until the correct credentials were identified. Each login attempt was recorded in the log file, allowing the activity to be reviewed from a SOC analyst perspective.

This demonstrates how repeated failed login attempts can indicate brute-force activity and why monitoring authentication logs is important during security investigations.

