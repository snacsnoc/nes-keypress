This is a 'driver' for the NES controller for use with a Raspberry Pi. For each button press on the controller press, it sends a key press. The main purpose of this is with an NES/SNES emulator.


Requirements
-----
[RPi.GPIO](http://pypi.python.org/pypi/RPi.GPIO) needs to be installed 


Usage
-----
Edit ` nes-keypress.py` to reflect your data, clock, and data pins on your Raspberry Pi. You can also edit the mapping of buttons to keypresses (A button corresponds to pressing F) for your situation.

Run it with ` sudo ./nes-keypress.py & ` to run it in the background. Start your emulator and begin using your NES controller.




License
-----
Copyright (c) 2012 Easton Elliott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 