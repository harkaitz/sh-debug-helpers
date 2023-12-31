# DEBUG HELPER

Scripts for debugging Go and C/C++ programs.

## Help

dlv-h-attach

    Usage: dlv-h-attach
    
    Attach to a running "dlv-h-ssh". You can use "dlv" from GNU Emacs.
    Put commands like "break main.CreateWebsite" in "DEBUG.dlv".

dlv-h-ssh

    Usage: dlv-h-ssh [-i] SSH [PROGRAM-REGEX]
    
    Connect to SSH server and attach to a PROGRAM's running process.

gdb-h-attach

    Usage: gdb-h-attach PROGRAM-BASENAME
    
    Search program and attach to it with GDB.

gdb-h-ssh

    Usage: gdb-h-ssh -e | SSH PROGRAM
    
    Connect to SSH server, search a running process with PROGRAM
    absolute pathname, and bind to it with gdbserver. You can then
    connect throw 127.0.0.1:9666 .
    
      -e : Execute `gdb -ex "target remote 127.0.0.1:9666" -i=mi`.
      -t : Execute `gdb -ex "target remote 127.0.0.1:9666"`.

ut

    Usage: ut ...
    
    Unitary test manager.
    
      File: UT.lst : NAME BINARY DIRECTORY
      File: UT.res : NAME {OK,OTHER} 
    
    Command line operations.
    
      -l      : List unitary tests (from results).
      -lf     : List failing unitary tests.
      -d NAME : Execute unitary test with DDD.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
