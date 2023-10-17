# Introduction to Embedded Systems and Microprocessors

### Fundamental Information

<img src="https://shorturl.at/cqvW9" width="400" height="400"/>

The ARM Cortex-M4 is a 32-bit microcontroller core designed by ARM Holdings. 
It's part of the Cortex-M series, which is specifically designed for use in microcontroller and embedded systems. 
The Cortex-M4 is known for its high performance and energy efficiency, making it suitable for a wide range of applications, 
including Internet of Things (IoT) devices, automotive systems, industrial control, and more.


ARM Cortex M processors are manufactor friendly due to their qualificaitons such as:
- Minimal cost, power and siicon area
- Nearly as at the same price as traditional 8 or 16 bit processor with its 32 bit version
- MCUs in ultra low power to high performance based applications
- Customizable with floating point, DSP (Digital Signal Processing) and MPU (Memory Protection Unit)
- Supports 240 external interrupts
- RTOS frinedly
- Rich instruction set and memory efficient


### Processor Core vs. Processor

<img src="https://shorturl.at/jpCO6" width="500" height="400"/>

Processor Core relies inside the processor and surrounded with busses and peripherals inside the structure.
Core is the basic fundamental computaion engine of the processor.

> [!IMPORTANT]
> Core consists of ALU (Arithmetic Logic Unit) where data computaion takes place and result will be generated. 

Processor also called CPU (Central Processing Unit). 
> [!WARNING]
> A CPU may have multiple cores. For example ARM Cortex M4 CPU has got only one core which is Cortex-M4 core.


### Processor vs. Microcontroller

<img src="https://shorturl.at/g2367" width="700" height="400"/>

Processor (CPU) is, heart of the microcontroller. Processor structure may re-design related to needs of the processor. 
Microcontroller may remove peripherals related to their operations. Microcontroller also has a block diagram as CPU.

> [!NOTE]
> ARM Cortex-M4F from that F means this processor comes with floating point unit
