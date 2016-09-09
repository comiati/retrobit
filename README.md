# RetroBit Game Console

This is a mix of retro game console with new technologies.

## Hardware

This is ARM9 processor running at 454Mhz with enough power to run linux and still in handsolder friendly TQFP package, which allow hobby DIY approach. RetroBit is even on 2 layer PCB and running at full speed.

######

- i.MX233 128-QFP Processor ARM926EJ-S runs up to 454MHz
- Memory 64MB DDR SDRAM (32Mx16)
- One USB host.
- Four input game pad controls.
- One degub UART.
- Composite video output.
- Stereo sound output.
- Micro SD Card.
- Power suply with power button and Led.
- Reset button.

## Software

ArchLinux package for the moment is with most advanced Kernel and enabled features so this is our choice for the moment to build examples.

This hardware is based on OLinuxXino of www.olimex.com
https://github.com/OLIMEX/OLINUXINO/tree/master/SOFTWARE/iMX233

For more informations send email to: fabianotraple@gmail.com
