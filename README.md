# xmodem99
An XMODEM application for the TMS9900 CPU.  This version is assumed to be invoked from a shell programme but can easily be modified to provide the filename arguments by other means.  

It is invoked from the command line using the syntax ***XMODEM FileName*** and will wait around 20 seconds for the first sender ***NAK*** .  The sender can be any compliant XMODEM sender.  For example it works using the menu Tera Term -> Transfer-> XMODEM->Send.

~~~

%
%XMODEM TEST
MODEM VERSION 1.5 - READY.
SUCCESS.
%

~~~
