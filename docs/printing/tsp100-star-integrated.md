## Symptom: Star TSP 100 series does not work with Star or Epson Direct Printing

## Resolution
The Star TSP 100 series (e.g., TSP143) is a raster-only printer, meaning that the printer was designed for the operating system print drivers to render a receipt into a raster image and send the raster image to the printer.

Because of that design limitation, It cannot natively handle Star Line Printing nor ESC/POS Epson style print commands. It is possible to configure the operating system print driver to print using ESC/POS (epson) commands, but it is using the print drivers to turn that into a raster image.

In the point-of-sale, you would have to configure the printer using the operating system drivers, and would not need to configure the printer for ESC/POS.

**The only way to use a Star TSP 100 series printer is with OS printing.**
