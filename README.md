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
- RTOS (e.g. event queue, message box) 
- ... 
 
 



The underlying OS is a multitasking operation system with real time capabilities (e.g. task priorities, message boxes).  


Introduce OpenAT Framework development at Sabik Marine

- [AirPrime Q2687](https://source.sierrawireless.com/devices/q-series/q2687/#sthash.UASnN7bJ.dpbs)  
- [AirPrime SL6087](https://source.sierrawireless.com/devices/sl-series/sl6087/#sthash.dJDe0jeE.dpbs)  
- [AirPrime SL8082BT](https://source.sierrawireless.com/devices/sl-series/sl8082bt/#sthash.G8gdrGkE.dpbs)  
  
## OpenAT Framework

The different AirPrime device series have different firmware versions. Some of these versions are  There are different version of the framework.




For SL8082BT series modem, download OpenAT Application Framework 2.54.2 Full Installer 
[OpenAT 2.54.2](https://source.sierrawireless.com/resources/airprime/software/open-at-application-framework-2,-d-,54,-d-,2,-d-,a1-full-installer-for-sl808xt_bt/#sthash.KTDjZNlc.dpbs)

or download [Developer Studio 3.6](https://source.sierrawireless.com/resources/airprime/software/open-at-application-framework/#sthash.51r519nn.dpbs) and install the OpenAT Framework 2.54.2 from the package manager inside the the developer studio.

### Required Packages

![Example](https://github.com/cdfromsabik/openat-training/blob/master/img/2_52_Packages.bmp)

## References

[AirPrime OpenAT Tutorial](https://source.sierrawireless.com/resources/airprime/training-and-tutorials/airprime---open-at-tutorial/#sthash.V8jnTEnX.dpbs)