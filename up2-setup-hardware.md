[Industrial IoT Workshop](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop) > [UP2 Getting Started Guide](README.md) > [Setup Hardware](up2-getting-started.md)

## Setup the Up2 Hardware
On the UP²* board locate connector 1 on the board. it is next to the screw that is circled in the photo.

![](images/1.png)

Line up pin 1 on the Grove Pi+ board with connector 1 on the UP² board, and carefully press down so that the pins on the Grove Pi+ board slide neatly into the connectors

![](images/2.png)

Connect the **Grove LCD Display** to any I2C port.  This is done so that when your board powers up it will display the IP address on the LCD.

![](images/8.jpg)

Plug the micro USB cable into the left side of the USB port on the UP² board.

![](images/4.png)

Connect the micro USB cable to your host computer.
**Note: Even though you might see lights turn on after you plug in the micro USB cable, this connection isn't enough to power your board reliably. The micro USB connection is used to set up the Arduino Create development environment. You'll connect the board to a power supply shortly.**

![](images/5.png)

Plug the Ethernet cable into the UP² board.

Plug the other end of the Ethernet cable into your router, connecting it to the same network as your host computer.
Note: Your host computer does not need to be on the same network as your UP² board.

![](images/6.png)

**Note: If you need to turn off your board, you can do so by pressing the small white button next to the blue LED, or you can simply unplug the power cable.**

![](images/7.png)

### Powering on your board
Power on your UP2 board. You should see a blue LED light up near the power connector.

We’ll come back to using the hardware after setting up the Arduino Create development environment.

[Setup the Arduino Create Environment with your UP Squared Board](setup-arduino-create-agent.md)
