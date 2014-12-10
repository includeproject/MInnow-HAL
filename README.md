MInnow-HAL
==========

Hardware abstractions layer for MInnowboard Max platform

Hardware abstractions layers (HAL) are sets of routines in software that emulate some platform-specific details, giving programs direct access to the hardware resources.  THe idea of this project is to create a HAL for minnow max platforms(http://www.elinux.org/Minnowboard:MinnowMax) 

THe basic requirements will be : 

Allow desktop applications to discover and use the hardware of the host system through a simple, portable and abstract API, regardless of the type of the underlying hardware

Each logical hardware device is represented as a D-Bus object, and its bus address is used as a unique identifier. Devices include abstractions like disk partitions and visible wireless networks. The device's functionality is exposed through D-Bus interfaces, and its state accessed through properties, a set of key-value pairs.

Description of basic HAL architecture: 
http://home.agh.edu.pl/~lkrzak/hal/hal_idea.pdf


