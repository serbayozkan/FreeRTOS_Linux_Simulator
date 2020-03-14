# FreeRTOS_Linux_Simulator

This workspace runs on Ubuntu 18.0.4 LTS with Eclipse CDT

## Notes
I cleared original main file and added only very basic single task that prints message periodically.

Original Files -> https://www.freertos.org/FreeRTOS-simulator-for-Linux.html

If you want to use original files, you should make a change in makefile to compile all FreeRTOS port files.

- Change makefile gcc command with "gcc -pthread -o"FreeRTOS_Posix" $(OBJS) $(USER_OBJS) $(LIBS) -lrt"
- In Eclipse settings you should uncheck "Generate Makefiles automatically" and indicate correct makefile.
