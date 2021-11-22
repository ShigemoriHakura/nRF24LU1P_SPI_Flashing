# nRF24LU1P_SPI_Flashing
Raspberry PI script to recover a NRF24LU1+ device via SPI.
It erases existing and possibly protected firmware while it saves the CHIP-ID and writes the nRF bootloader binary.

boot24lu1p-f32_padded.bin is from https://github.com/al177/buspirate_nrf24lu1p

# Connection
* GND   =   6
* RESET =   18
* PROG  =   22
* SCK   =   23
* MOSI  =   19
* MISO  =   21
* CS    =   24