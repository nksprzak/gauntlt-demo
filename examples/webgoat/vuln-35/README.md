File Name: vuln35attack.py

Vuln-ID: vuln-35

Team: newcastle

Members: Ahmed Alsabag, Danish Jaffer

Vuln-Area: Access Control Flaws => Using an Access Control Matrix
Problem Description: Exploit WebGoat access control matrix. 
User Larry is member of [User,Manager] and has unauthorized 
access for Account Manager that is restricted to admin group only"

Path:
The file are located in /home/hacker/vuln35 

Required Python Modules: 
sudo apt-get install python-pip
pip install requests

What it will return:
If the vulnerability exists, gauntlt will fail
	-The python file will print vulnerability exists

If the vulnerability does not exist, gauntlt will pass
	the python file will print, vulnerability does not exists
