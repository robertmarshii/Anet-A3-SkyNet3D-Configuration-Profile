# Anet-A3-SkyNet3D-Configuration-Profile
Anet A3 SkyNet3D Configuration Profile

Original Profiles: https://github.com/thijsk/Skynet3d/tree/master/SkynetV2.3.2/Configuration%20Profiles

SkyNet3D Firmware: https://github.com/thijsk/Skynet3d

Anet Board Driver: https://github.com/SkyNet3D/anet-board

U8glib Graphics Library: https://github.com/olikraus/U8glib_Arduino


A3 Firmware Guide:
1. Download: Anet-Board at https://github.com/SkyNet3D/anet-board
2. Download: Skynet3d at https://github.com/thijsk/Skynet3d
3. Download: U8glib_Arduino at https://github.com/olikraus/U8glib_Arduino
4. Put the A3 configuration.h file into the "SkynetV2.3" firmware folder
5. Put Anet-Board files here: "C:\Users\*\Documents\Arduino\hardware\anet\avr" (make folders if missing)
6. Download and install Arduino Software (IDE) on Windows
7. Open Arduino Software (IDE)
8. Tools>Board> Set to "Anet V1.0"
9. Tools>Programmer> Set to "AVRISP mkII"
10. Tools>Port> Set correct COM Port (usually COM5) 
11. File>Open... "Desktop\Skynet3d-master\SkynetV2.3.2\SkynetV2.3.2.ino"
12. Sketch>Include Library...>Add .Zip Library - Choose "\Desktop\U8glib_Arduino-master.zip"
13. Verify
14. Upload

If you have trouble with verification, try reinstalling Arduino, opening a blank sketch and closing the SkyNet one, closing Arudino 
and then opening the SkyNet sketch again.
