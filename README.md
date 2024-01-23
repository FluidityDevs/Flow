# Flow (Early 2024) - The future of unlocking.
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

**Changelog for 2.0**

1. 4 new elevation methods are used instead of 3
2. flowd is a new background process to re-elevate the system upon startup
3. logKit logs all progress to any connected flash drives with a "Logs" folder on them
4. Completely rewritten all scripts
5. Rebranded to Flow instead of Fluidity Ocean/Unlocker, including new naming and a new drive icon
6. Thinned down the image to not include so many empty documents and folders as templates, making the ISO image under 350MB
