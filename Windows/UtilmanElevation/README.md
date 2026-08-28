# Utilman Elevation

This is an insainly stupid way to elevate to Admin but...

## Instructions

1. Go to the power menu
2. Hold shift and press restart
3. Click troubleshoot
4. Click Command Prompt
5. Run the batch file `run_in_recovery.bat`
6. Reboot your computer
7. Go to the login screen
8. Click the assessability button
9. Run the batch file `run_in_login.bat`
10. Set a password following the instructions in the output of the terminal
11. Then login to Administator through the usual user menu and if it's not showing up just use the other user option.

## How does it work

Well, because windows give you access to a cmd in the recovery menu, you can just go to the C drive's system32, make a backup of utilman.exe and copy the cmd.exe with the name utilman.exe, because windows doesn't check before running it you gain a cmd as the user SYSTEM.\
Which is all done for `run_in_recovery.bat`\
\
`run_in_login.bat` enables the admin account the normal way without any work arounds. Passwords arn't aways needed but depending on the computer there can be policies to require a password, or a password with cirtian rules.
