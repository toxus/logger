[home](../README.md)

# Logger Revisions

version 0.10 - 20208-08-06
- level: debug
- transport.file: targetFile is full path to file
- isDebugActive
- options.debug to active the debugger

version 0.9
- auto change transports to [transports]
- fix: empty message in super.log

version 0.4.0
- added toConsole property

version 0.3.2
- add the rootDirectoy to the WinstonLogger to define where the log files are written 
- added a pipe to connect multiple loggers