#Note:

This is not the official Vectras VM repository, this repository was created to suit users on YouTube channel Nguyen Bao An Bui. And this is the official Vectras VM repository: https://github.com/xoureldeen/Vectras-VM-Android

#What's new?

- It is no longer required to select ROM ICON and ROM DRIVE.
- Connect to the new server to use AUTO SETUP.
- The store is supported.
- The message dialog says there is no support for 32-bit.
- Store items are downloaded through the browser.
- Fixed a bug where nothing happened when tapping the Create button.
- Added the virtual machine list data error dialog is corrupted.
- Added the dialog suggests creating a new virtual machine when the virtual machine list is empty.
- Tap the thumbnail in the virtual machine creation interface to change the image.
- Select thumbnails with more formats.
- Fixed the first time virtual machine creation failure.
- Fixed the Save Changes button being disabled when editing virtual machine information.
- Do not automatically restart the app when creating a new virtual machine.
- Fixed black screen when using PowerPC.
- Added small note about adding ROM and CDROM.
- No need to switch architecture.
- Improved stability when creating new virtual machines.
- Added dialog about CPU missing necessary instructions.
- Added dialog asking for permission to access storage.
- Added UEFI for qemu-system-aarch64.
- Added a button to completely shutdown Vectras VM.
- Don't auto-open VNC when qemu is stopped.
- Don't auto-close VNC when the OS is booting.
- Added tap and hold shut down button to temporarily exit VNC activity.
- Change the Vectras VM shutdown button to kill all Qemu processes.
- The Shut down button in VNC activity will kill current Qemu processes.
- 32bit support.
- Added warning dialog if your device does not support 64bit.
- AUTO SETUP will directly install qemu instead of spending extra time downloading bootstrap file.
- Added VNC screen open button.
- Fixed keyboard not showing up in VNC activity.
- Audio support with Termux.
- Automatically disallow virtual machines from running when your device does not support Multi-threaded TCG.
- If you do not set a thumbnail for the virtual machine, the thumbnail will be automatically selected to match the virtual machine name.
- Fixed an issue where the ADD button would be disabled after selecting ROM DRIVE or CDROM.
- If you click the ADD button while you have not added a hard drive or storage device to the virtual machine, a warning dialog will appear.
- New setup method.
- More stable VNC display.
- Automatically suggest using Single-threaded TCG if your device is not eligible for Multi-threaded TCG.
- Do not start the VM when it is detected that it is already running.
- Removed "-nodefault" to fix audio device error.
- New update check method.
- The default name of the new VM is "New VM".
- Fixed a bug where the file containing the virtual machine list data could not be created.
- New simple setup interface.
- Allow landscape rotation on setup screen.
- Only detect issue when clicking ADD button on new virtual machine creation screen.
- New Qemu params editing screen for easier editing.
- Changed some icons to match the feature.
- Changed location to create new qcow2 file.
- Screen suggests to create new virtual machine if no virtual machine in list.
- Added option to delete all virtual machines.
- New Gilroy font.
- Added Arabic language support for some features.
- Support creating virtual machines with Create command (https://play.google.com/store/apps/details?id=com.anbui.cqcm.app).
- ROM Store is back.
- Improved interface for ROM Store.
- Vectras VM will now connect to this GitHub repository for online operations.
- Improved stability for ROM Store.
- Allows you to choose to keep ROM files and CD ROMs when deleting a virtual machine.
- Automatically exits ROM Store when you're done creating a virtual machine.
- Added a dialog warning of a fatal error that occurred in Setup.
- Fixed cvbi file import.
- ROM Store now supports cvbi.
- Automatically use default Qemu params if ROM Store does not provide Qemu params information.
- New folder location to store ROMs.
- Added error dialog about cvbi.
- Automatically search and add disk file if cvbi does not contain file containing information.
- Added ID for VM.
- Better delete all related files when choosing not to keep files when deleting VM with VM ID.
- Automatically retain files needed by other virtual machines when you choose not to retain files when deleting a virtual machine.
- Automatically add information if cvbi file does not contain information from ROM Store.
- Added cleanup feature.
- Added Go to ROM store button on main screen when no virtual machine is created.
- Changed interface on architecture selection screen.
