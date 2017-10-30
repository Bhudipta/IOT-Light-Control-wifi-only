# IOT-Light-Control-wifi-only

For this Project
You will need
1. Raspberry Pi 3
2. LED
3. 270 ohm resistor

The OS of choice is Raspbian

Connect the positive pin of LED to GPIO 17 pin and the negative to a 270 ohm resistor.
The other side of which is connected to GND pin.

Make sure your Pi is up to date
sudo apt-get update

Install git:
sudo apt-get install git-core

Obtain WiringPi using git
git clone git://git.drogon.net/wiringPi

To build/install WiringPi library

cd wiringPi
./build