# wall-calendar

This is a program to create a wall calender in the form of a web page.

It is written in the HistoryCal Script language
and is intended to serve as an example of its use.

### Running HisoryCal Script

HistoryCal Script is a spinoff from the [HistoryCal Program](https://github.com/nickmat/HistoryCal).
During the development of the Cal library and HistoryCal GUI program,
a command line program was also being developed.
This was mainly being used for quick tests but since version 0.3,
the test program and interactive program have been separated.
When version 0.7 of the GUI HistoryCal is released, it is the intention
that a version of the interactive command line program be released with it.

The program is named **hcs** and is intended to be added to the path
so it can be run from anywhere.
Using the -e flag the program can be used to run a hcs script file
with the output going to std out.
This is how this script is intended to run, with std out piped to a html text file.

On windows, the code is run as follows.

`hcs -e wall-calendar.hcs`

And should result in 12 output files, such as [cal/cal-2020-6.htm](https://nickmat.github.io/wall-calendar/cal/cal-2020-6.htm).
