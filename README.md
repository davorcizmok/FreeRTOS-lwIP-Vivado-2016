# FreeRTOS_lwIP_Vivado_2016
FreeRTOS/lwIP (XAPP1026) for Xilinx Zynq devices using Vivado 2016. This port is compatible with Xilinx Vivado 2016.2 and was tested on the boards Zedboard, RedPitaya and Z-turn, but should work on a Xilinx ZC702 board also. This repository is based on the repository posted by Don Stevenson in the FreeRTOS forum called "FreeRTOSlwIP (XAPP1026) for Xilinx Zynq devices using Vivado 2014.2". 

In order to make compatible the previous repository with Vivado 2016 were modified the tcl scripts of the application examples. Also was modified the file /sw/repo/bsp/lwip140_v2_1/src/contrib/ports/xilinx/netifxemacpsif_physpeed.c in order to make it compatible with the RedPitaya and Z-turn boards.

