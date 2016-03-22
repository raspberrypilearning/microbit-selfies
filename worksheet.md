# micro:bit selfies

In this resource you will make a BBC micro:bit controlled selfie booth with a Raspberry Pi and camera module using Python. This is a great way to get started with hardware and simple text programming.

## The First Step



Mu final code:

```python
from microbit import *

while True:
    if pin0.is_touched():
        display.scroll("say cheese!")
        sleep(500)
        pin1.write_digital(1)
        sleep(5000)
```        
