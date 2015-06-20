# gslX680
Android Version of GslX680.ko that Loads Firmware from a File Originally by Joe Burmeister.
This is a Modification of the GSLX680 driver from the Allwinner A31 SDK using Joe Burmeisters gslx680-ts-sunxi Driver as a
Basis. This incoeporates the changes needed to load the firmware from a file in the /system/etc/firmware folder. The driver
is hardcoded to look for a file name gslX680.fw for the firmware information. Use the Firmware extractor script by Joe Burmeister
to pull the firmware from your original driver.

This is a link to the compiled driver packaged with .bat files and the firmware extractor to pull your current driver and extract the firmwares from a working Tablet. Once you have flashed a firmware to the tablet that does not have a working gslx680 driver the
bat files will push in the new driver and you can select the appropriate firmware to have it pushed in, you may need to try
more than one of the extracted firmwares to locate the correct one for your tablet. http://www.4shared.com/archive/KxG9DHUcba/GslX680_New_Driver_and_Firmwar.html
