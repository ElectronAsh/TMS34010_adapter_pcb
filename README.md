# TMS34010_adapter_pcb

# USE AT YOUR OWN RISK!

This adapter PCB should allow you to connect a TMS34010 CPU to FPGA dev boards like the DE10 Nano, and maybe the DE0.

But it is currently UNTESTED, and does not include proper voltage translation buffers between 3V3 and 5V.

The current design only has some series resistors on each CPU output pin, with some clamp diodes on the FPGA GPIO headers.

There is an inherent risk of not using proper voltage translation, but I would personally risk it for short-term use for development.

If I get time, I will add proper voltage translation to the board.
The current design was just a way to get a quick version done for the few devs who might be able to make use of it.

![Eagle PCB screenshot](/images/Eagle_PCB_screenshot.png)

![PCB photo, older proto](/images/PCB_photo_older.jpg)

