## Lesson 1 Blinking LED

---

Circuit is 3.3v to 220 ohm resistor to long leg (anode) of LED.
Then GPIO 17 to short leg (cathode) of LED.

### Important Python

  * import RPi.GPIO as GPIO
  * import time
  * GPIO.setmode(GPIO.BCM)
  * GPIO.setup(17, GPIO.OUT, initial=GPIO.HIGH)
  * GPIO.output(17, GPIO.LOW)
  * GPIO.output(17, GPIO.HIGH)