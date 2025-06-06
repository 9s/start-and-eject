# perception.cx setup launcher

a faster and more safe way to run the perception.cx setup executable.

# what it does

this tool performs the following actions in order:

1. kills specific background processes (steam.exe, eadesktop.exe)
2. clears the contents of the %temp% folder
3. launches `setup.exe` located in the same directory
4. waits a few seconds
5. attempts to safely eject the usb drive the executable was run from

## usage

1. download the `launcher.exe` file [from the latest release](https://github.com/9s/perception-launcher/releases/tag/nightly)
2. place `setup.exe` and `launcher.exe` in the same folder on a usb drive
3. run the executable (e.g. `launcher.exe`)
4. the tool will handle cleanup, setup execution, and usb ejection automatically

logs will be printed to the console if visible. all actions are performed silently in the background.
