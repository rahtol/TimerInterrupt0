# Using an ESP32 HW timer to control a 4-digit LED Display.

The multiplexing necessary to control the 4-digit LED display is fully interupt-controlled, no polling.
The display is realized as a separate class with somewhat generic interface.

The main routine uses another HW timer to implement a 1Hz counter on the display.
