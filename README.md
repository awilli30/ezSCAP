Script to make running OpenSCAP scans simple.

I built ezSCAP,a lightweight tool written entirely in Bash to automate the workflow of OpenSCAP. 

How ezSCAP Simplifies Your Security Scans:

No More Long Commands: Say goodbye to complex flags and path arguments. Run comprehensive scans with simple, intuitive execution.
No Profile ID Memorization: Easily select or target compliance profiles without hunting down long string identifiers every single time.
By removing the friction and cognitive load from running security audits, AutoSCAP helps practitioners focus on what actually matters: remediating vulnerabilities and keeping systems secure.

NOTE: OpenSCAP needs to be downloaded before using AutoSCAP 

Command to get OpenSCAP: sudo dnf install openscap-scanner scap-security-guide

curl -0 https://raw.githubusercontent.com/grayteamtech/ezSCAP/refs/heads/main/ezSCAP.sh
