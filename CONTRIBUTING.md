# CONTRIBUTING.md for Model01-Firmware, or, How to build

## Setting up

1. Open Arduino IDE
2. Tools | Boards | Board Manager.  Search for `keyboardio`.  Install the
   latest version of "Kaleidoscope keyboards".  Hit Close.
3. File | Open Model01-Firmware.ino in this directory.
4. Tools | Board | Kaleidoscope Keyboards | Keyboardio Model 01

## Building

1. Sketch | Verify/Compile

   You may get errors from the CapsLock plugin if it has been broken by
   a Kaleidoscope change.  If so, edit it in the Kaleidoscope-CapsLock
   directory, which is a git submodule.

2. Unplug the keyboard, hold Prog, and plug the keyboard back in.
3. Go to Tools | Port, and choose the "Keyboardio Model 01" port.
3. Sketch | Upload
4. Unplug the keyboard and then plug it back in.
