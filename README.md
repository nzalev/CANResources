# CAN Resources

The [Uwindsor P1 page](https://github.com/UWindsor/CarHackingResearch) contains some instructions for the P1 and some research papers. There is also [P1 documentation](https://docs.macchina.cc/p1-docs/getting-started)

The kernel level documentation on SocketCAN and CAN interfaces is [here](https://www.kernel.org/doc/html/latest/networking/can.html). This can be used to communicate via the CAN interface through raw sockets in C.

There is a linux package which provides utilities for working with CAN interfaces and messages, [can-utils](https://github.com/linux-can/can-utils)

There look to be two solid Python libraries which provide access to CAN interfaces
- [python-can](https://github.com/hardbyte/python-can)
- [socketcan](https://gitlab.com/Menschel/socketcan)


There are some other repos on Github dedicated to collecting CAN resources
- [awesome-canbus](https://github.com/iDoka/awesome-canbus)
- [vehicle-security](https://github.com/wtsxDev/Vehicle-Security)

## OBD2 Pinout
[]()|[]()|[]()|[]()|[]()|[]()|[]()|[]()| 
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | 2 | 3 | G | G | 6 | 7 | 8 |
| 9 | 10| 11| 12| 13| 14| 15|+12v|

Pin   | Purpose
:---: | :---
1 | Manufacturer Defined
2 | J1850 (PWM +)
3 | Manufacturer Defined
4 | Ground
5 | Ground
6 | CAN High
7 | KWP K
8 | Manufacturer Defined
9 | Manufacturer Defined
10| PWM -
11| Manufacturer Defined
12| Manufacturer Defined
13| Manufacturer Defined
14| CAN Low
15| KWP L
16| +12V
