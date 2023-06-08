A homebrew application for the Nintendo DSi. Allows the user to place stickers over a live-view of the camera and save photos. Use the left and right button to change what sticker you are placing. Use b button to switch cameras.

Run make in home directory to build the program. Program cannot be run on any DSi emulators as they do not emulate the camera. devkitpro must be installed in order to build the program. The libcamera library(https://github.com/FTC55/libcamera) must also be in a parent directory to be able to build. An already built .nds file is included in the repository, this is the file that is loaded onto the DS and run.

TODO: Get capture working without crashing.
