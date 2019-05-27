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

This requires root privileges.

