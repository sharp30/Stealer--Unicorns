# Unicorn Stealer
A Trojan stealer, looks like a unicorns game.

*The project was done during applying to a CyberSecurity company.


## Stealing ##
The program steals:
  * keylogging
  * IP address the computer is talking with.
  * OS details
  * Running Proccess
  * Screenshots
  * Connected User and groups.
  
Every a minute the program writes all data into a txt file (placed in a hidden directory).

## Processes Closing ##
The virus will close 5 running process:
  * Wireshark
  * Fiddler
  * tasklist
  * taskmgr - Task Manager
  * procexp - Process Explorer

## Dll Injection ##
The program also injects a dll:

  - Changes the computer background.
  - Edits the Run directory in the computer registery.


## GUI ##
 basic GUI done with WinForms.
 
<center> <img src="https://github.com/sharp30/Stealer--Unicorns/blob/master/unicorns-gui/unicorns%20app.png" width="300" height="300"> </center>
