# OpenAT Embedded Software 
 
OpenAT Embedded Software consists of a firmware, a real time operating system and a set of optional plug-ins, that extend the capabilities of the OS (e.g. internet plug-in). The API of the OS represents a layer on top of the firmware. And the OpenAT application is build on top of that OS-API. Firmware and OpenAT application are seperate binaries, that are present in the embedded module memory. 
 
The API of the OS is called *Application Development Layer* or **ADL**. It abstracts hardware peripherals and software interfaces. 
 
- AT commands 
- OS (e.g. memory management)
- GPIO 
- GPRS/EDGE 
- DOTA 
- GSM/SMS 
- FCM 
- RTOS (e.g. events, messages) 
- ... 
 
## Developer Studio 
 
You develop the application using the **Developer Studio** that is based on the [Eclipse IDE](https://www.eclipse.org/ide/). The programming language is C and the used compiler is [GCC](https://gcc.gnu.org/). There are two different version of the Developer Studio that you will use for development. 
 
[Developer Studio 2.3.2](https://source.sierrawireless.com/resources/airprime/software/open-at-application-framework/#sthash.k9FUJeyN.gjcJ9o9q.dpbs) is used for the [AirPrime Q2687](https://source.sierrawireless.com/devices/q-series/q2687/#sthash.pc3op1oO.dpbs) and [AirPrime SL6087](https://source.sierrawireless.com/devices/sl-series/sl6087/#sthash.dJDe0jeE.dpbs). 

[Developer Studio 3.6](https://source.sierrawireless.com/resources/airprime/software/open-at-application-framework/#sthash.51r519nn.dpbs) is for the ~newer~ [AirPrime SL8082BT](https://source.sierrawireless.com/devices/sl-series/sl8082bt/#sthash.G8gdrGkE.dpbs), which runs wih [Firmware 7.54.x](https://source.sierrawireless.com/resources/airprime/software/open-at-application-framework-2,-d-,54,-d-,0,-d-,a1-full-installer-for-sl808xt_bt/#sthash.yAeqlZOu.dpbs), that is not supported by *Developer Studio 2.3.2*.
 
### Required Packages
 
![Example](https://github.com/cdfromsabik/openat-training/blob/master/img/2_52_Packages.bmp)
 
## References
 
[AirPrime OpenAT Tutorial](https://source.sierrawireless.com/resources/airprime/training-and-tutorials/airprime---open-at-tutorial/#sthash.V8jnTEnX.dpbs)  
 
