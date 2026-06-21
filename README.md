# Security-Event-Detection-System

## Overview
This project is a Python-based security event detector. It analyzes sample log data and identifies suspicious activity such as failed login attempts, successful logins after failures, new user account creation, and suspicious PowerShell activity.

## Features
- Detects multiple failed login attempts
- Detects successful login after failed attempts
- Detects new user account creation
- Detects suspicious PowerShell commands
- Assigns severity levels
- Maps findings to MITRE ATT&CK techniques
- Provides recommended actions

  ## Technologies Used
- Python 3
- Dataclasses
- Enums
- -MITRE ATT&CK Framework  

## How to Run
1. Install Python 3
2. Download the project files
3. Open the folder in VS Code
4. Run:

```bash
python security_event_detector.py

## Project Members
- Adrian Campbell
- Xavier Eldridge
- Omar Juarez
