# What's up?
This script is intended for an Ubuntu home media server to listen for CEC-messages and start Kodi when TV goes on.
For more details look into the source code.

# Prerequsites
* python3 (v3.10.12 works well)
* libCEC >= v6.0.2 with Python bindings
* Kodi is set up to run as it expected:
  * a window manager like OpenBox is setup
  * you'd also need to setup Kodi to exit when TV goes off

In Linux the script shall run with privileges sufficient to open COM-ports and run Kodi.

Start the script when either TV is on and Kodi already running or TV is off and Kodi stopped.
