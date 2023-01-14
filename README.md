# projectproposalMKEL1123 (3%)

**INSTRUCTION**
Propose a project that suits the capability of the STM32
Good applications include: 
  1. TinyML
  2. Real-time IoT. RTOS must use STM32 capability to sleep (to save power) and send data to cloud server.
Input/output interfacing is mandatory
Do not propose an application can easily be done on a slow Arduino:
  1. Previous bad projects include plant-watering system and human detection by infrared
Do not propose an application that requires a full-blow PC
  1. Previous bad projects include recognizing disease in X-ray images

Sketch a system architecture

Hardware Requirements:
Must use Cortex-M4 processor. Any other processor is not acceptable.
Can use any board including Nucleo-64, Black Pill or Discovery.
Must use at least two physical input/output ports not including GPIO
  1. The popular ones are I2C, SPI and I2S. You can also use ADC, PWM, etc.
  2. It is  acceptable to use the same port twice as long as the connected devices are different (for example temperature sensor and LCD using I2C
Software Requirements:
Must use STM32CubeIDE or Keil MDK. Any other IDE is not acceptable.
Must use software libraries to fully utilize STM32 capabilities. Examples:
  1. CMSIS-NN, CMSIS-DSP, CMSIS-RTOS,
  2. STM32Cube.AI
  3. TensorFlow Lite for Microcontrollers.
  4. coreMQTT
  5. uTensor
Write the proposal in Github

Github URL for Part 2.2. The proposal contains the following sections:
Previous works. A selection of related works by others


Use cases. How the system is used. (What is a use case?)


System Architecture (Hardware). Put a block diagram of the system showing the CPU and major peripherals used.


Algorithm (Software). Describe and justify the software libraries used.



