# Components included with Flow (as of 2.1.1)

### Scripts
**flowd** - Internal Disk + WIM file - Transfers to internal drive immediately upon booting Flow, background process for general maintenance and persistence. Maintained separately from Flow.

**environment** - Internal Disk + WIM file - Does most of the heavy lifting with account modification, software removal, and task scheduling, also resets Registry keys to previous state so Windows can cleanly boot again.

**unlock** - WIM file - Performs the transfer of **environment** and **flowd** to the internal disk. Does Registry modifications to trigger the bootscreen command prompt exploit.

**updater** - External Storage - Transfers updated versions of flowd to the internal disk.

**installer** - External Storage - Allows you to install flowd manually to the internal disk if you have administrator permissions and do not wish to boot full Flow.

### Components of Scripts

**logKit** - Present in **environment** and **unlock**, stores logging information used by Flow, optional component.

### Programs

**Firefox** - Browser of choice useful for evading Edge's required sign-on

**Process Hacker 2** - Advanced task manager, useful for inspecting processes and running programs with elevated system users

**Rufus** - Flashing new Flow media
