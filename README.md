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

Run `MakeWinPEMedia /ISO <Directory For Source> <Directory For Output Image>.iso`

That's all you need to compile Flow into an ISO, but I do recommend Rufus to flash your USB, and DISM GUI to make any system modifications.

*Instructions (USB, from source):*

Start the Deployment and Imaging Tools Environment as an Administrator

Run `MakeWinPEMedia /USB <Directory for Source> <Drive Letter>`

And that's all you need to compile Flow while flashing directly to a USB device.

*Instructions (USB, from ISO):*

1. Open Rufus
2. Select your flash drive and drag in the ISO file
3. Show advanced format options
4. Uncheck "Create extended label and icon files" (as Flow already includes some)
5. Press start, and confirm writing in ISO image mode

Done! You now have a bootable UEFI USB drive for Flow, including all included scripts

**Includes these projects:**

https://processhacker.sourceforge.io/

https://www.mozilla.org/en-US/firefox/

https://github.com/FluidityDevs/flowd

Free to use by anyone, you just have to build/flash it yourself.
