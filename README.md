## Directories:

+ The *RTOS/Source** directory contains the RTOS source code, and contains
  its own readme file.

+ The **RTOS/Demo** directory contains a demo application for every official
FreeRTOS port, and contains its own readme file.

+ The RTOS/Test** directory contains the tests performed on common code and the portable layer code, and contains its own readme file.

See RTOS/SourceOrganization](http://www.freertos.org/a00017.html) for full details of the directory structure and information on locating the files you require.

The easiest way to use FreeRTOS is to start with one of the pre-configured demo
 application projects (found in the FreeRTOS/Demo directory).  That way you will
have the correct FreeRTOS source files included, and the correct include paths
configured.
Once a demo application is building and executing you can remove
the demo application file, and start to add in your own application source
files.

### See also -
+ [Quick Start Guide](http://www.freertos.org/FreeRTOS-quick-start-guide.html)

+ [FAQ](http://www.freertos.org/FAQHelp.html)
