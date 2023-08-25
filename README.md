# Fluidity Ocean - Fast, hidden, utilitarian.
A basic Windows PE environment to unlock certain computers from Windows 8.1 to 11 using the Bootscreen Command Prompt Exploit.
Built with the 2022 Windows 11 ADK.

**How to build:**

*Prerequisites:*

Windows Assessment and Deployment Kit (For Windows 11 22H2) and the Windows PE (Preinstallation Environment) add-on, both from Microsoft's website.

An x86_64 computer with UEFI support (Needed for build and usage)

Rufus, from https://rufus.ie (Flashing to a USB device, optional)

DISM GUI (Optional, CLI can be used instead, DISM is used for system modifications.)

*Instructions (ISO):*

Start the Deployment and Imaging Tools Environment as an Administrator

`MakeWinPEMedia /ISO <Directory For Source> <Directory For Output Image>.iso`

That's all you need to compile Fluidity Ocean into an ISO, but I do recommend Rufus to flash your USB, and DISM GUI to make any system modifications.


**Includes these projects:**

https://www.opautoclicker.com/

https://processhacker.sourceforge.io/

https://www.mozilla.org/en-US/firefox/


Free to use by anyone, you just have to build/flash it yourself.
