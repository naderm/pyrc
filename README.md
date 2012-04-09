Pyrc
=====

A simple, one file script to wrap around a virtual terminal and an irc client for easy irc session management.

Dependencies
------------

Currently supports screen and tmux for the virtual terminal and irssi for the client. Simply having irssi and either screen or tmux installed and in $PATH is enough.

Usage
-----

Starting or reconnecting to a session is as simple as:

    $ pyrc

You can configure the default virtual terminal and irc client by using the -e and -i flags.

For more information, see the help flag:

    $ pyrc -h
    Usage: pyrc [options]
    
    Options:
      -h, --help            show this help message and exit
      -s, --start           Just start the irc client, don't connect to it
      -c, --connect         Don't start the irc client, only connect to it if
                            possible
      -e EMU, --emu=EMU     terminal emulator to use: screen, tmux [default:
                            screen]
      -i IRC, --irc=IRC     irc client to use: irssi [default: irssi]
      -n SESSION, --session=SESSION
                            name to give to terminal emulator session

