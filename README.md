ME7_95040sum
============

BSD Licensed tool written in C for Bosch ME7.x EEPROM data dump checksum validations. Specifically validates dump files for 95040 IC 512byte dumps.

This tool is a conversion from one written by Julex in C#
(see http://nefariousmotorsports.com/forum/index.php?topic=1727.0)

I wrote this conversion (into C) so it can also run on non Windows platforms. This code should cross compile across any OS and any platform easily.

This tool is specifically for validation and re-calculation of 512 byte dump files which have been
dumped from a 95040 IC EEPROM chip (which contains exactly 512 bytes [or 4096 bits] ).
