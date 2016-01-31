Eclipse configuration for NUCLEO STM32F401 programming & debugging
====

#Eclipse installation & Buildtools

- Install latest Eclipse IDE for **C/C++ Developers** version at https://eclipse.org/downloads/
- Install GNU ARM Eclipse (follow instructions at http://gnuarmeclipse.github.io/install/)
- Install openOCD (debug tools) (http://gnuarmeclipse.github.io/openocd/install)

#Miscellaneous

You can add a Terminal view in Eclipse :
- In Eclipse : Install New Software > TM Terminal
- In Eclipse : Add this to the list of repos : http://rxtx.qbang.org/eclipse
    - Install the latest plug-ins.
- For windows users : http://jlog.org/rxtx-win.html
    - Download 'RXTXcomm.jar' and install it in the 'lib/ext' folder of the Java VM 
    - Download 'rxtxSerial.dll' and install it in the 'bin' folder of the Java VM
- Restart Eclipse, Windows > Show view > Terminal > Create terminal
