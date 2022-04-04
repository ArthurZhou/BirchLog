# BirchLog
A convenient way to make logs like Log4j in Java.

[Take me to the official page](https://github.com/ArthurZhou/BirchLog)
***
###### <span id="110">*This document is for BirchLog1.1.0(BirchLog110)*</span>
What`s new in 1.1.0?

1.More styles:credit, end, crash

2.Fix the bug that "\033[x;x;xm" will write into the log file

3."WARNING:", "ERROR:", "DEBUG:", "CRASH:" will no longer display, but still in the log file

4.Add plainLogger and liteLogger function
***

## What`s BirchLog
BirchLog is a logger write on Python3.7.2 that can make log files easily like Log4j.All the thing you need to do is 
***Import and Input***.This version includes BirchLog, BirchLog *lite* and BirchLog *plain*

## Overview
*Run the .py file to get an example output and a log file!*

[yyyy-mm-dd hh:mm:ss|<session name>]Normal log

<span style="color:red">[yyyy-mm-dd hh:mm:ss|<session name>]Warning log</span>

<span style="color:yellow">[yyyy-mm-dd hh:mm:ss|<session name>]Error log</span>

<span style="color:pink">[yyyy-mm-dd hh:mm:ss|<session name>]Debug log</span>

<span style="color:cyan">[yyyy-mm-dd hh:mm:ss|<session name>]Credit</span>

## How to use
### logger
Use `from BirchLog<version number> import logger` and `logger(logFile, logText, sessionName, type, color)` to apply.

logFile: file to write

logText: text to write

sessionName: session name

type: log type("write"(write only), "print"(print only), ""(default))

color: log color("warn"(yellow), "error"(red), "debug"(pink), "credit"(cyan), "end"(white bg), "crash"(red bg),
""(default))

Run the .py file is also ok!

### Other functions
For more import helps, you can have a look at tester() function.
It shows you how to use logger, plainLogger and liteLogger!

## Credit
Made by ArthurZhou.Follow GPL-3.0 Licence.
