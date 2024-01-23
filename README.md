# Flow - The future of unlocking.
A basic Windows PE environment to unlock certain computers from Windows 8.1 to 11 using the Bootscreen Command Prompt Exploit.
Built with the September 2023 Windows 11 ADK with Windows PE 22H2 plugins.

**How to build:**

*Prerequisites:*

Windows Assessment and Deployment Kit and the Windows PE add-on, both from Microsoft's website.

An x86_64 computer with UEFI support (Needed for build and usage)

Rufus, from https://rufus.ie (Flashing to a USB device, optional)

DISM GUI (Optional, CLI can be used instead, DISM is used for system modifications.)

*Instructions (ISO):*

Start the Deployment and Imaging Tools Environment as an Administrator

`MakeWinPEMedia /ISO <Directory For Source> <Directory For Output Image>.iso`

That's all you need to compile Flow into an ISO, but I do recommend Rufus to flash your USB, and DISM GUI to make any system modifications.

**Includes these projects:**

https://processhacker.sourceforge.io/

https://www.mozilla.org/en-US/firefox/


Free to use by anyone, you just have to build/flash it yourself.
