# RGB LED Matrix Panel

- a cheap way to build DMD (dot matrix display) for your pinball machine
- there are different sizes (2-5mm per pixel) and pixel resolutions (up to 64x64) available
- individual panels can be chained together to create even bigger display
- the panel itself contains barely any logic and all the work (timing, mixing colors etc.) has to be done on the device that's driving the display


## P2.5-2121-64X64-32S-ZX-M1
- sample panel from AliExpress, $15 + $5 shipping (February 2020)
- 64 x 64 pixels, 160mm wide, 160mm high (2.5mm per pixel)
- HUB75 connector
- 5V input voltage
- 1:32 scan-rate (you can only update 2 rows at once)
- integrated circuits on the board
  - 74HC245TS (transceiver)
  - TC7258GN (line scanning driver chip)
  - ICN2037BP (constant current LED sink driver)
