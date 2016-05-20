# blinkcontrol
command line tool to automate controlling blink cameras

This tool will allow you to controll your blink cameras simply by issuing commands from your command line. This is useful for automating these functions. available controls are:

blinkcontrol status

-> returns either "true" or "false" depending on if your cameras are armed

blinkcontrol arm

-> attempts to arm your cameras and returns status after arming

blinkcontrol disarm

-> attempts to disarm your cameras and returns status after arming

requirements:

-Curl

Installation:

To install download the zip file to your *nix computer (compatible with linux, mac, etc) and extract. Cd to the directory you extracted the files to and run:

"sudo ./installbc"

after install is complete run:

bcsetup

bcsetup will prompt you for your blink credentials. once installed run the commands as above.
