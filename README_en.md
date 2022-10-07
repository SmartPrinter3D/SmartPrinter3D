# SmartPrinter3D

Single Board Computer Software for 3D Printing

## Getting Started

### Installation

1. Download and extract the SmartPrinter3D image corresponding to your single board computer
1. Use [balenaEatcher](https://www.balena.io/etcher/) to burn the image to SD card
1. Insert an SD card into your single board computer, connect a display, and you can also connect a mouse and keyboard if necessary
1. Connect your 3D printer to the single board computer via USB port
1. Turn on the single board computer and wait for the system to start
1. Make sure the `AUTO_REPORT_TEMPERATURES` and `EXTENDED_CAPABILITIES_REPORT` lines are uncommented in the Marlin firmware. Otherwise, temperatures will not be displayed correctly

### Initial setup
1. On the main page, click the ```Settings``` button and in the ```Language``` section, select the system language that suits you
1. In the ```Other``` section, you can disable the display of the cursor if you use only the touch screen
1. In the ```Printer``` section, specify the parameters of your 3D printer for the system to work correctly with your 3D printer and save
1. Reboot the system
