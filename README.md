# mcping
Ping multiple hosts, curses interface

## Motivation
I was missing an MTR-like program, having multiple hosts in a nice UI and pinging them in a loop. There is / was mping, but I didn't find it in my favorite Linux distribution nor a source-code. So I was thinking about a program using Curses (NCurses?) with Perl.

## Required Perl packages
* Curses
* Time::HiRes
* Net::Ping
* Getopt::Long

## Usage
`sudo ./mcping 127.0.0.1 127.0.0.2 127.0.0.3 8.8.8.8 127.0.0.4 172.16.0.1`

![Sample screen gif](images/mcping-example.gif)

This requires root privileges.

## Notes
The program requires a screen size of at least 80 x (number of hosts + some more lines).
This isn't checked by now. If the screen looks weird, well, that could be the cause.

