# FreeRTOS_ESAT
This is a short FREERTOS over QEMU simulation project with realization of Master/Slave functionality

#Prerequisites
FreeRTOS 2022 version available
arm-gnu-eabi tools
QEMU for arm

In command line, please enter following command to start ESAT MASTER/SLAVE Demo

-> qemu-system-arm -machine mps2-an385 -cpu cortex-m3 -kernel D:/workspaces/FreeRTOSv202212.01/FreeRTOS/Demo/CORTEX_MPS2_QEMU_IAR_GCC/build/gcc/output/RTOSDemo.out -monitor none -nographic -serial stdio -s -S
