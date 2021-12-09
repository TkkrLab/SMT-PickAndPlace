# SMT-PickAndPlace
this git repository contains all the files required to setup and configure the smoothieboard. 

# Custom smoothie firmware
Each motor is driven by a [TMC4671+TMC6100-BOB](https://www.trinamic.com/support/eval-kits/details/tmc4671-tmc6100-bob/) board. 
These boards are configureable through SPI. To get the smoothieboard to configure the boards I had to write a new driver. 
The firmware.bin contains precompiled firmware for the board, but if you wish to compile the software yourself, check out the SPIDriver branch in my smoothieware fork: [smoothieware repository](https://github.com/marklendering/Smoothieware)

You can also choose to configure the board through other means, like a [esp-32 board](https://github.com/TkkrLab/trinamic-tmc4671-tmc6100-bob-arduino). Keep in mind that the settings in this repository are for a specific motor.

# Trinamic software
I used the Trinamic IDE software to get the correct settings. You can get the [TMCL-IDE here](https://www.trinamic.com/support/software/tmcl-ide/).
You will need a [USB-2-RTMI](https://www.trinamic.com/products/modules/details/usb-2-rtmi/) or [Landungsbruecke ](https://www.trinamic.com/support/eval-kits/details/landungsbruecke/) to communicate with the BOB board.


# Linear motors
The designs for the linear motors can be found in the [Linear Motor](https://github.com/tkkrlab/linearmotor) repository.


# Hardware
 TODO...
