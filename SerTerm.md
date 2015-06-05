# Introduction #

SerTerm is a serial terminal allowing users to connect to serial ports (both real ports and USB-to-serial ports).


# Details #

**Description:**
Users have the ability to set the baud rate, send ASCII data to a serial port, and receive data from a serial port. Received data can be displayed in two formats: ASCII and 16-bit integers in hexadecimal.

**Origin:**
SerTerm was originally created to talk to XBee ZigBee modules, then updated to display 16-bit integers for use with PIC microcontroller development.

**Future:**
Although it's not as feature-rich as some other programs (RealTerm, Terminal, etc.), it continues to evolve as more features are needed by its users. Someday it will have all the features of these programs, and more.

**OS Compatability:**
Because it's programmed in JAVA, SerTerm should be able to run on many platforms. It has NOT been tested on UNIX/Linux/Mac. SerTerm has been tested on Windows XP and Vista, and works on both systems.

**Requirements:**
To run SerTerm, the Java Runtime Environment must be installed, as well as the RXTX library.
To develop SerTerm, the Java SDK must be installed, as well as the RXTX library.
From the RXTX main page:
"RXTX is a native lib providing serial and parallel communication for the Java Development Toolkit (JDK). All deliverables are under the gnu LGPL license."
Installation of the RXTX library is a simple procedure documented here: http://rxtx.qbang.org/wiki/index.php/Installation.


**Development:**
SerTerm is programmed in NetBeans due to the simplicity it lends to creating GUIs and auto-generation of code.

**Updates/Improvements:**
Users are encouraged to report bugs and request features, as well as tinker with the code themselves. If users improve the software and add features, they are encouraged to report these for the benefit of others in the community.

**License:**
This project (SerTerm) has no license. Use it as you see fit.