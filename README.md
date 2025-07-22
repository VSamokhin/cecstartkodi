# What's Up?
This script is intended for an Ubuntu home media server to listen for CEC-messages and start a Kodi instance when TV goes on.
For more details look into the source code.

# Prerequisites
* python3 (v3.10.12 works well)
* libCEC >= v6.0.2 with Python bindings
* Kodi is set up to run as it's expected:
  * a window manager like OpenBox is configured to start and host Kodi
  * you'd also need to configure Kodi to exit when TV goes off

In Linux the script shall run with privileges sufficient to open COM-ports and start Kodi.

Execute this script either when TV is on and Kodi is already running or when TV is off and Kodi stopped.
