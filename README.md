openocd_bbb
===========

OpenOCD for BeagleBone Black (for GsoC Project PRU/JTAG)

- the project is to provide an OpenOCD interface using the PRUSS subsystem and a Cape containing a CPLD, for very high-speed JTAG signalling
- base code for PRU provided by Pantelis Antoniou

Implementation Plan

 - bitbang JTAG interface for OpenOCD, using gpio
 - bitbang JTAG interface for OpenOCD, using pru code to operate the pins
 - if the Cape is ready, extend bitbang interface using the CPLD
 
 - review performance, and various options for high-speed operation
 

Other details COMING SOON
