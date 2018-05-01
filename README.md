SPIVI
=====

This library implements a simple SPI interface for LabVIEW.

The library can be used with any NI PXI Digital I/O Module with Hardware-Timed Digital I/O.

Its main features are:
- Transmission of data from a U8 Array by the MOSI signal.
- Reception of data from the SOMI signal as U8 Array.
- Control of the CS signal.
- Variable length of bytes transmitted/received determined by the length of the U8 Array MOSI data.
- Variable data rate.


License
-------

The SPIVI library is distributed under the terms of the MIT License.

Requirements
------------

The VIs are written in LabVIEW 2016.

The library can be used with any NI PXI Digital I/O Module with Hardware-Timed Digital I/O. Note: I have only tested it with a PXIe-6537 module.

It needs the "SPI Digital Waveform Library (SDW)" distributed by National Instruments. You can download an install it from http://www.ni.com/example/31163/en/.

It needs the NI-DAQmx drivers distributed by National Instruments. You can download an install it from http://sine.ni.com/nips/cds/view/p/lang/es/nid/10181/.

Credits
-------

This library is based on concepts extracted from "Serial Protocol Communication Reference Design for Digital Waveform Devices", available at http://www.ni.com/example/31200/en/. This reference design isn´t necessary to use the SPIVI library.

Installation
------------

You can copy all the files to a folder named "SPIVI" inside your project folder and add the file "SPIVI.lvlib" to your LabVIEW project.

Sample
------

There is a sample project demostrating the use of the library in the folder "Samples".

![Test SPIVI](Samples/Test%20SPIVI.png "Test SPIVI")
