[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 3

## Topics covered

Peripherals architecture in the raspberry pi

GPIO (General purpose input/output) pins and their flexibility

Experiments with LEDs and the Gerboard

Setting up simple traffic light examples



## Personal Notes and research following this session
A raspberry Pi has a main chip called the Broadcom BCM2837, its called a system on a chip (SoC) because many important things are combined into one chip; 4 GPU cores, a memory unit, a graphics processor(GPU) and controllers for USB, Ethernet and GPIO. So, a lot of the Pi’s essential hardware is built into this single chip.

[Petrikowski, N.P., 2014. Getting to Know the Raspberry Pi. The Rosen Publishing Group, Inc.](https://books.google.co.uk/books?hl=en&lr=&id=AX5hDwAAQBAJ&oi=fnd&pg=PP1&dq=using+a+gertboard+with+raspberry+pi&ots=nOpbhSMA1O&sig=o68ndCB8k-VqkJFkvMuoJ3eESKA&redir_esc=y#v=onepage&q=using%20a%20gertboard%20with%20raspberry%20pi&f=false) 

GPIO stands for General purpose input/output, it’s a set of pins on the raspberry Pi that you can program to do different tasks. The Pi has a 40-pin connector for GPIO and inside the system, the pins are labelled GPIO 0-25. But different Pi models can have different pin layouts so make sure to check the correct pin map. The GPIO pins can be used as input (reads information), output (e.g. turns an LED light on) some of them are more advanced and can act as serial ports for communication, provide clock signals and connect sensors or boards. You can connect electronic parts to the GPIO using a Gertboard.



## Exercises and results
installed Node RED on the Raspberry Pi and connected it to the Gertboard



## Summary of learning
