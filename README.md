
OBS Studio Lua Scripts
======================

About
-----

This is a small collection of [Lua](http://www.lua.org/) scripts
for automating certain tasks in the video/audio stream
mixing software [OBS Studio](https://obsproject.com/).

The individual scripts are:

- [clone-template-scene.lua](clone-template-scene.lua):<br/>
  Clone an entire source scene
  (template), by creating a target scene (clone) and copying all
  corresponding sources, including their filters, transforms, etc.

- [refresh-browser-sources.lua](refresh-browser-sources.lua):<br/>
  Refresh all <i>Browser Source</i> sources.

Installation
------------

1. Clone this repository:<br/>
   `git clone https://github.com/rse/obs-scripts`

2. Add the individual scripts to OBS Studio with<br/>
   **Tools** &rarr; **Scripts** &rarr; **+** (Add Script)

License
-------

Copyright &copy; 2021 Dr. Ralf S. Engelschall (http://engelschall.com/)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

