**Welcome to the JAGIP (Job Alerts for Government Internship Pathways) Bot.**
![](https://imgur.com/a/Nf8zA5Y)
The purpose of this bot is to poll a USAJOBS API key in a relatively light, efficient, and reliable manner. 

Every 60 minutes (will be configurable later), it uses a list of "job codes" and filters to evaluate and return
available jobs fitting that criteria. While this bot is targeted for internships, it can be easily reconfigured.

This bot is in a very early alpha - expect bugs and weird behavior. I haven't tested it beyond my own Linux
machine - this program does contain a certain level of logging, so if you really enjoy this program and wish
to support it, please shoot me any logs/crash data and I'll work on it ASAP. It is mostly here for me to tweak with using git and my repository as an update source. 

Requirements:

 - Python
 - A machine to continuously run the program
 
 That's it for requirements - there's an experimental install script in place here. It should automatically configure a venv and install packages via pip.


Setup is as follows:

 - Download the python file and job codes file into a new folder.
 - Edit job codes if desired - a fairly comprehensive list is included, but it's mostly cyber/comp-sci related.
 - Run the python file. 
 
 Simple, no? My favorite motto is KISS - Keep It Simple Stupid, and so I do. 

