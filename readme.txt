This is a port of Lee Davison's Enhanced BASIC 2.22 for the Thistle computer.

Building
--------

To build it, you'll need a copy of the CC65 tool chain from http://www.cc65.org/
and a suitable version of 'make'. Just typing:

```make```

in this directory should re-build everything. You'll get a listing,
some object files, and the ROM image itself.


Usage
-----

Copy the 'basic.bin' program to the root of a OpenComputers hard drive and boot
up the Thistle EEPROM. Type 'load basic.bin' followed by 'run' and you'll be
presented with EhBASIC.

At the first prompt, type 'C' for a Cold Start

When prompted for free memory, type: $A000

Note that EhBASIC only accepts upper case keywords and commands, enabling caps
lock is recommended to easily use it.


Changes from the EhBASIC 2.22
-----------------------------

  - Code syntax changes to allow assembly with the cc65 tool chain.

  - Memory map and input/output modified for Thistle.

  - Boot messages and prompts changed.

EhBASIC is copyright Lee Davison <leeedavison@googlemail.com>


Original EhBASIC 2.22 README
----------------------------

 Enhanced BASIC is a BASIC interpreter for the 6502 family microprocessors. It
 is constructed to be quick and powerful and easily ported between 6502 systems.
 It requires few resources to run and includes instructions to facilitate easy
 low level handling of hardware devices. It also retains most of the powerful
 high level instructions from similar BASICs.

 EhBASIC is free but not copyright free. For non commercial use there is only one
 restriction, any derivative work should include, in any binary image distributed,
 the string "Derived from EhBASIC" and in any distribution that includes human
 readable files a file that includes the above string in a human readable form
 e.g. not as a comment in an HTML file.

 For commercial use please contact Lee Davison at leeedavison@googlemail.com
 for conditions.
