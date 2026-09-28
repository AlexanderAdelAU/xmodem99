# xmodem99 - CRC 1k
An XMODEM application for the TMS9900 CPU.  This version is assumed to be invoked from a shell programme but can easily be modified to provide the filename arguments by other means.  

It is invoked from the command line using the syntax ***XMODEM FileName*** and will wait around 20 seconds for the first sender ***NAK*** or C is CRC is selected.  CRC is the default error detection and correction protocal and the packet or record length can either be 128 or 1024 bytes depending on what the sender is configured to configure.  The sender can be any compliant XMODEM sender.  For example it works using the menu Tera Term -> Transfer-> XMODEM->Send.

~~~

%
%XMODEM TEST
MODEM VERSION 1.5 - READY.
SUCCESS.
%

~~~
