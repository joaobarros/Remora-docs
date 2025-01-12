Hardware
========

Raspberry Pi
------------

As the hard realtime requirements are offloaded onto the controller board, Remora can run on RPi 3B, RPi 3B+ and RPi 4B.

.. image:: ../_static/rpi-pinout.png
    :align: center


Controller Boards
-----------------

In general any controller board that is based on an LPC1768, LPC1769, STM32F407. STM32F429, or STM32F446 microcontroller can be used, provided that an SPI interface is available. "Smoothieware" compatible controller boards are common and include:

* Mks-Sbase V1.3 - Tested. Requires on board jumper to allow the J3 header connector to be used for SPI communication
* Bigtreetech SKR V1.3 - Tested
* Bigtreetech SKR V1.4 - Tested. For TURBO version use LPC1769 firmware version.
* Re-ARM - Under test
* Bigtreetech SKR V2.0 - Tested. Both versions. 
* Bigtreetech Octopus v1.1 - Tested.
* Bigtreetech Octopus PRO - Tested. Both versions. 

.. toctree::
   :maxdepth: 2
   
   Mks-Sbase
   SKRV13
   SKRV14
   Re-ARM
   skrv2
   octopus


