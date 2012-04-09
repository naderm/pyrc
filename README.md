Pyrc
=====

A simple script to wrap around screen, tmux, and irssi.

Usage
-----

Starting or reconnecting to a session is as simple as:

    $ pyrc

You can configure the default virtual terminal and irc client by using the -e and -i flags.

For more information, see pyrc -h:

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

