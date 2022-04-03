# BirchLog
A convenient way to make logs like Log4j in Java.

[Take me to the official page](https://github.com/ArthurZhou/BirchLog)
***
###### *This document is for BirchLog1.0.0(BirchLog100)*
What`s new in 1.0.0?

everything is new!
***

## What`s BirchLog
BirchLog is a logger write on Python3.7.2 that can make log files easily like Log4j.All the thing you need to do is 
***Import and Input***

## Overview
[yyyy-mm-dd hh:mm:ss|<session name>]Normal log

WARNING:<span style="color:red">[yyyy-mm-dd hh:mm:ss|<session name>]Warning log</span>

ERROR:<span style="color:yellow">[yyyy-mm-dd hh:mm:ss|<session name>]Error log</span>

DEBUG:<span style="color:pink">[yyyy-mm-dd hh:mm:ss|<session name>]Debug log</span>

## How to use
Use 'from BirchLog<version number> import logger',then use 
'logger(logFile, logText, sessionName, type, color)' to apply.

logFile: file to write

logText: text to write

sessionName: session name

type: log type("write"(write only), "print"(print only), ""(default))

color: log color("warn"(yellow), "error"(red), "debug"(pink), "(default))

Run the .py file is also ok!

## Credit
Made by ArthurZhou.Follow GPL-3.0 Licence.
