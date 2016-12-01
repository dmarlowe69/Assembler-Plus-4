This is an continuation of my earlier work to reverse engineer
the Commodore Macro Development System's (MADS) Assembler.
The pervious attempt would compile to the the original binary
but was not relocatable. I found a version of the asssmbler at
plus4 world that had been hacked and modifed to work on the PLUS 4.
Comparing the two versions allowed me finish the work and now the
source code is relocatable. This one loads on the Plus 4 at $1001 and
runs with SYS 4111. 

Also included is a program that will take the assembler output "interface"
file and convert it into a PRG file. The orginal MADS package included a 
loader program and then the monitor was used to save the PRG file.

Denton Marlowe
November 2016