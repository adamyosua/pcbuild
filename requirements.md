# Requirements

## Use Case

- run of the mill office work
  - libreOffice
- windows/linux development
  - Cross platform Application python/C development
  - Embedded Development
    - Probably both TI (CCS) and Microchip (??)
  - EDA
    - **PCB design**-  KICad. Requirements are on [this page](https://www.kicad-pcb.org/help/system-requirements/). They don't have heavy recommendations but I need to be aware that my graphics card supports openGL or some shit like that.
    - **FPGA development** -  (heavy use of multithreading and CPU usage). I need to link what Xilinx recommends here. I know that in general heavy CPU usage is present.
- Gaming
  - Minecraft
  - Ages 
- OS Virtualization
  - virtualBox
- Scientific Programming
  - octave simulations
- Dual Boot System
  -  Windows/Linux
- Personal data storage management
  - I would like to try to get a personal cloud up and running

## Hardware Requirements

### Needs

- multicore (needed for FPGA development)
- strong linux compatibility
- better than my laptop processor from 2013 (idealy more cores, faster clock more modern fab, i5 level or higher)

### Wants

- Over clocking
- audio jack
- extra peripherals
  - probably want ability for 4 monitors if its not too exspensive
  - should have a ton of USB ports
    - keyboard
    - mouse
    - hardrive caddy
    - extra drives
    - development board or 2
    - devboard communication port?
    - flashdrie or 2
  - it would be nice to have some older stuff to mess around with like serial or VGA
  - Maybe an extra PCIe slot?

## Software Requirements

I should only fill out the edge cases here until I get my bill of materials. The only software that should be here is stuff that pushes the limit of the PC or notes about linux only or dependencies on hardware.



### Linux Distro

I want to aim for Debian. My fall back in xubuntu. It would be cool if I could get a completely free one like Trisquel but I would probably put that in a virtual machine. I would also like to do a real fine tuned custom distro like Arch? or gentoo?; I'm not sure which one. I can also probably make that a VM.



### The biggest Hogs are going to be

- Vivado
- Games
- Virtualization
- Kicad
- Octave (not as important)