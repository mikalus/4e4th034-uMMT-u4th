# 4e4th+uMMT on MSP430G2553 MicroBox - IAR Kickstarter snapshot

Forth MiniMultiTool for your Embedded Experiments 

Based on 4e4th Release 0.34 for the TI MSP430G2553 Value Line LaunchPad Develpoment Tool (MSP-EXP430G2), Rev. 1.5 chip.  
One of the few processors still available in the breadboard friendy 20 Pin DIL Package.  
The MMT will run ON this chip.

4e4th is based on CamelForth MSP430 V0.3 that Bard Rodriguez has created for the MSP430F1611. 

## Assembling uMMT
The project has been created using IAR Kickstart IDE. Open it as existing project there. 

The free version of IAR can only program projects up to 4K. If the file is larger, you can use a BSL scripter tool like the FET-Pro430 Flash Programmer by Elprotronic. To be able to use an external scripter tool, **IAR must be configured** to output the file in Intel Hex Format. Select the option "Output file override" under Project/Options/Linker/Output and "other output format = intel extended". This will create a file 4e4th.a43 using Intel Hex format in the folder Debug/Exe. This file can be programmed into the MCU using the FET-Pro430 tool. 

## Need the Programmer?  
https://www.elprotronic.com/  
"Lite FET-Pro430 Elprotronic Programmer" burns image into MCU.

## More books  
https://wiki.forth-ev.de/doku.php/en:projects:litlist  
and  
https://wiki.forth-ev.de/doku.php/en:projects:pintaske_s_electronic_forth_bookshelf

Have fun.

----
tbd ...

## Use uMMT
Start your favourite Terminal program and ... ??

## New to the TI LaunchPad?  
 see: ???

