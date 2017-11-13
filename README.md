# Xbee-Xbox


Code for making Xbox controller(connected wirelessly\wired(USB)), send data to Xbee router.

Things needed:
Visual Studio, latest version
XBox controller,
Pair of Xbees(one connected to robot(presumably), the other to computer),
XCTU, latest version.

In XCTU, you can monitor the data being sent to the coordinator(robot, presumably) from the router(computer).

In line 20 of the main.cpp file, there is a string called "COM7": change this to whatever the COM port is to the Xbee in your laptop.

After that, you can use the Local Windows Debugger and it will display the values you are currently pressing or reading from the sticks and the buttons

This was originally written by Zotto, I added the code for it to work with digital buttons.
