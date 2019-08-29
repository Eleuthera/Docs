### EI_OSABI

|Value  |Alias         |
|-------|--------------|
|0      |SYSV          |
|1      |HP-UX         |
|2      |NetBSD        |
|3      |GNU/Linux     |
|4      |GNU/Hurd      |
|5      |86Open        |
|6      |Solaris       |
|7      |Monterey      |
|8      |IRIX          |
|9      |FreeBSD       |
|10     |Tru64         |
|11     |Novell Modesto|
|12     |OpenBSD       |
|13     |OpenVMS       |
|14     |HP NSKernel   |
|15     |AROS          |
|16     |FenixOS       |
|17     |Nuxi CloudABI |
|97     |ARM           |
|256    |Standalone    |

Even though GNU/Linux is right there, you need to resist temptation.
The spec says we should use 0. Unless we want to use extensions.

