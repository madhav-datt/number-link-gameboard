#
# Makefile for numberlink game board generator program
# Typing 'make' or 'make numberlink' will create the executable file.
#
# Copyright (C)   2015    Madhav Datt
# http://www.gnu.org/licenses/old-licenses/gpl-2.0.html
#

# compiler to use
#
CC = g++

# flags to pass compiler
#
CFLAGS  =

# target executable name
#
default: numberlink

# for executable file numlink:
#
numberlink:  numberlink.cpp
	$(CC) $(CFLAGS) -o numberlink numberlink.cpp

# remove old executable files:
#
clean: 
	$(RM) numberlink *.o *~