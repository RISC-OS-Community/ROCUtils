# CmdToVar

This is a ANSI C written utility to execute a command from RISC OS Obey and store the output to a RISC OS ENV Variable.

The code is mostly completed, however it requires:

1) Remove ShareCLibrary dependecies
2) Build it as a Transient Utility
3) Add memory managed using RMA (OS_Module)

