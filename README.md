# MINIDISC

Arduino sketch to write names to a minidisc deck. It combines the remotes RM-D27M (regular remote) and RM-D10P (expensive keyboard)

Components:
- Arduino nano
- IR led
- 470R resistor
- BC547 transitor

Optional
- visible led (optional)
- 100R resistor

Pinout:
- Connect pin 3 of the arduino to 470R 
- Connect 470R to the base of BC547
- Connect GND of arduino  to the collector of BC547
- Connect emitter of BC547 to cathode of the IR Led (short pin of the IR led)
- Connect anode of the IR Led (long pin) to 5V 

Optional:
- Connect anode of visible led (short pin) to GND of arduino
- Connect cathode of visible led (long pin) to 100R
- Connet 100R to pin 6 of arduino
