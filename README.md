# Motion Activated and Gesture Initiated control
This project was made for my final year of university project.
The project is also known as "MAGIC", which stands for "Motion Activated and Gesture Initiated control"

Essentially this code lets you control an RC car with hand gestures in front of a camera.

The goal was achieved using OpenCV & Python to recognise the hand gestures and then sending this data over to the Arduino wirelessly which then controls the car.

A custom Radio transmitter and receiver was built for communicating between the car and the Arduino and thus the radio signals work well in traffic and up to a range of 25m [that's the max we've tested]

This project was built upon the hand gesture code written by [Sadaival](https://github.com/Sadaival/Hand-Gestures)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the libraries.

```bash
pip install Serial
pip install numpy
pip install opencv-python
```

## Usage
In the mix.py file
```python
arduinoData = serial.Serial('com6',9600)
```
This is the serial port at which I was listening. Make sure to put the same port and serial as defined in the Arduino.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
