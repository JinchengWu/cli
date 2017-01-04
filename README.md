# cli
A simple command list interfac, use the configure file, will generate the command tree.

## target
The command tree generate by the configure files.

## Usage
cli 
 -d configure files direction
 -f specific configuration file

## Configure file format
Top Node, Command, Sub-command,....,Description,Call Shell
==================================================================
"p-mode","show","cpu","show cpu used situation",/sbin/show_cpu_use
