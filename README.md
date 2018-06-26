# a3 = AAA = Andys Arduino Architecture

Why "a3"? Well "AAA" sounds a bit too much like a taxi company trying to come first in the phone book. "a3" is far more nerdy. 

"a3" is a collection of classes that enable construction of Arduino sketches that in a modular fashion not more complicated than the wiring of the hardware. It will consist of quite a large number of classes (more than the average Arduino library), which will be reconisable by the common name prefoc "a3_". 

The architecture centres on the idea of a software I/O channel (a3_IO), which can be used to link functional modules and hardware drivers together. The collection will include a number of drivers mapped specifcally to popular hardware I/O controllers, such as multiplexers and demltiplexers, in and out shift registers, and LED matrix controllers.

It is intended for hobbyists as well as professional, so I focus mainly on hardware that costs less than a large latte in my local coffee shop. I use an Arduino Micro, available on eBay for less than the price of a pint. 

The collection is currently under development and will be released a bit at a time in coming months, as and when I have fully tested them on real hardware.  

I plan to provide a series of tutorial projects (based on my test scenarios) to familiarise users with the collection, the libraries and the way of working with them. 

