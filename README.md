PIC18F CDC Example
==================

TL;DR:

A stripped-down, minimum hard- and software [CDC][1] example for
PIC18F devices, derived from my [initial approach][3] to implement a PIC18F14K50 into [M-Stack][2].

---
### NEWS

#### Changes 2017/10/XX

    - initial upload
    - uNcLeAn mess (but working)

---
### USAGE

This project contains a complete and ready to load MPLab X project file.  
Different MCUs can be selected via the build configurations.

[...]

---
### SUPPORTED DEVICES/CONFIGURATIONS

 - XC8, v1.44 PRO mode

#### 18F14K50

  - 12MHz crystal, 4xPLL, HS
  - no external USB pull-ups
  - interrupt functionality currently not supported
  - [...]

[...]


---
### RANDOM NOTES

    For changes made to the original library, search the source code
    for "FMMT666". I usually [tm] documented everything. Almost. Sometimes.

=

    Harmony is crap.

=

    Don't code and AVR.

=

    .o/


---
### TODO

to be continued...


---
Have fun  
FMMT66(ASkr)


[1]: https://en.wikipedia.org/wiki/USB_communications_device_class
[2]: http://www.signal11.us/oss/m-stack
[3]: https://github.com/FMMT666/m-stack
