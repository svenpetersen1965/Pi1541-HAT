# Pi1541-HAT
Just another Pi1541-HAT. Please refer to Steve Whites project page (https://cbm-pi1541.firebaseapp.com/), who had the idea for the project and develops the software running in the Raspberry Pi.

There are several Pi1541-HATs, which are all good, nevertheless I have decided to make my own HAT. 

1. It has detachable display, switches and IEC-Bus boards

2. There is a barrel connector on the IEC-Bus Board, so no requirement for using the micro USB and no side entry for the enclosure required.

<img src="https://github.com/svenpetersen1965/Pi1541-HAT/blob/master/Pi1541/Pi1541-HAT/Rev.%201/pictures/0439_-_Pi1541-HAT_test_set-up.JPG" width="300" alt="Pi1541 with the detachable switch and iec board">

I have made it this way to add flexibility to the HAT when it comes to be installed in an enclose and also alows a lower profile enclosure, since the high IEC-bus jacks are not above HAT level.

As a replacement for the switch board, a pcb with a rotary encoder with push button has been developed. This adds a quite bit more comfort while navigating through the directories. It mimiks the select, up and down button. This way, it works with the regular firmware (even before 1.21). Depending on the amount of text to be scrolled on the display, some pulses might get lost, which is hard to notice and does not reduce the usability.

<img src="https://github.com/svenpetersen1965/Pi1541-HAT/blob/master/Pi1541/Pi1541-HAT/Rev.%201/pictures/1810_-_Pi1541_in_case.JPG" width="300" alt="Pi1541 withRotary Encoder Board in plastic enclusore">

<img src="https://github.com/svenpetersen1965/Pi1541-HAT/blob/master/Pi1541/Pi1541-HAT/Rev.%201/pictures/1806_-_Pi1541_open.JPG" width="300" alt="Pi1541 withRotary Encoder Board (case open)">

The kernal revision v1.21 supports the connection of a rotary encoder. Rev. 2 of the HAT PCB provides the connection of a rotary encoder module (KY-040), which is widely available on ebay etc. This is ment to be as a cheaper alternative for the otary encoder board of this project. 

<img src="https://github.com/svenpetersen1965/Pi1541-HAT/blob/master/Pi1541/Pi1541-HAT/Rev.%202/pictures/3182_-_KY-040_rotary_encoder.JPG" width="300" alt="KY-040">
