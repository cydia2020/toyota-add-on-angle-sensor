Arduino Project to send AS5047P magnetic rotary encoder value to CAN, based on @zorrobyte 's angle sensor project.

The project is originally intended for the Seeed Studio CANBed, your mileage may vary if you use other boards.

Parts:
1. Arduino (ATMega32U4)
2. LS7366R
3. CAN Bus Shield or adapter
4. AS5047P magnetic encoder

Hook-up Guide:
1. Connect Arduino to CAN Bus Shield
2. Connect LS7366R to Arduino via SPI bus
3. Connect AS5047P module to LS7366R via A/B/GND/5V
4. Connect CAN Bus to application
