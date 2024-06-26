# xlaserpointer
Linux utility to change the cursor into a strobey laser pointer for screencasts and presentations, a la the feature in Google Slides and most other slide deck applications.

![Application Demo](doc/demo.gif)

## Usage

Start the program, and good luck on your prezzi <3

To exit, send SIGINT / Ctrl + C

## Requirements

To build:
- libx11-dev
- libxi-dev
- libcairo2-dev

To run:
- X11
- A compositing window manager

## TODO

- Non-compositing X11 systems
- Wayland support
- Try to minimize dependencies

## License

Copyright (C) 2020, Naomi Alterman

Permission is hereby granted, free of charge, to any person obtaining a copy 
of this software and associated documentation files (the "Software"), to deal 
in the Software without restriction, including without limitation the rights 
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell 
copies of the Software, and to permit persons to whom the Software is 
furnished to do so, subject to the following conditions: 

The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software. 

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE 
SOFTWARE.
