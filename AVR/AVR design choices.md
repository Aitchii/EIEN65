Design considerations for AVR Board

What features do we need?

* PWM output signal
* Bidirectional serial communication rx and tx
* Analog input for fine tuning
* Two digital input signals
* SPI programming interface
* Power and testing LEDs
* 1MHz or 8MHz clock freq?



1MHz was chosen as clock freq



Pin config:



Output pins:

* PWM: 15 (PB1)
* SPI:

MOSI: 17 (PB3)

MISO: 18 (PB1)

SCK: 19 (PB5)

RST: 1 (PC6)

VTG: VCC

GND: GND

* USART TX: 3 (PD1)
* LED1: connected to the PWM signal
* LED2: 10 (PB7)
* LED3: 13 (PD7)



Input pins:

* Analog ADC: 26 (PC3)
* USART RX: 2 (PD2)
* Encoder 1: 24 (PC1)
* Encoder 2: 23 (PC0)



VCC: 



GND: 



RESET: 1 

