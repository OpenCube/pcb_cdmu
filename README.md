OpenCube CDMU
=============

The OpenCube Command and Data Management Unit (CDMU) is an embedded Linux computer. It coordinates the various functions of the spacecraft. In particular, it peforms the following tasks:

 * Telemetry pre-processing and encoding
 * Telecommand decoding
 * Communication session management
 * Resource allocation
 * Fault mitigation

In its current version, it consists of a BeagleBone Black board mounted on a custom circuit board with CAN bus transceivers. In the future, the board will also include a latch-up protection circuit, external memory (FRAM) and an external watchdog circuit. Eventually, the BeagleBone will be replaced with an AM3359 processor and its support components.
