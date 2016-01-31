![http://www.threatmind.net/trinux.png](http://www.threatmind.net/trinux.png)

## What is it? ##
[Trinux: A Linux Security Toolkit](http://trinux.sourceforge.net/legacy/) was a ramdisk-based Linux distribution that was under active development from 1998-2003. This new project (i.e. ubuntutrinux) seeks to integrate elements (and code, where appropriate) of Trinux with the Debian/Ubuntu mkinitramfs infrastructure to allow easy development and packaging  [Ubuntu](http://www.ubuntu.com) binary (and ultimately package and repository) compatible ramdisk distributions using recent 2.6.x kernels. As before, the most common use is network security monitoring and analysis. See [this blog entry](http://blogfranz.blogspot.com/2007/04/10-days-of-trinux-9-years-later.html) for more on philosophy and design principles.

Although there might be some overlap in the tools available, this project does not seek to provide a pen-testing distro along the lines of [Backtrack](http://www.remote-exploit.org/backtrack.html) or [Knoppix-STD ](http://s-t-d.org/). If you are looking for a platform to run [Nessus](http://www.nessus.org) or [Metasploit](http://metasploit.org) I encourage you to look elsewhere.

## What is going on? ##

See [project activity wiki page](http://www.threatmind.net/secwiki/UbuntuTrinux/ProjectActivity) or [subscribe to trinux-talk](https://lists.sourceforge.net/lists/listinfo/trinux-talk) mailing list. Also see [project milestones](http://www.threatmind.net/secwiki/UbuntuTrinux/ProjectMilestones) for anticipated releases and feature sets. Also check out [open issues](http://code.google.com/p/ubuntutrinux/issues/list) to see if problems you may be experiencing have already been reported.

## Getting it ##
There are severals kinds of project deliverables:

  1. [Development snapshots](http://www.threatmind.net/ubuntutrinux/) - builds in between releases that are reasonably stable, but not as polished or well-documented as formal releases
  1. Distribution releases (meaning things are usable, iso's, ramdisks, kernels, etc.) will be available [Trinux Sourceforge Site](http://sourceforge.net/project/showfiles.php?group_id=3301)
  1. Toolkit releases (meaning, the scripts to build your own distribution) are available on [this site's downloads page](http://code.google.com/p/ubuntutrinux/downloads/list) and in the [subversion repository](http://ubuntutrinux.googlecode.com/svn/)

## Using it ##

  * [BootProcess](http://www.threatmind.net/secwiki/UbuntuTrinux/BootProcess) - how to boot ubuntutrinux from CD-ROM, ISO, USB, PXE, etc.
  * [Remote Administration](http://www.threatmind.net/secwiki/UbuntuTrinux/RemoteAdministration) - how to access ubuntutrinux through SSH2, serial console, or telnet
  * [Netflow](http://www.threatmind.net/secwiki/UbuntuTrinux/NetFlowCapture) - not just for routers anymore!

## Developing your own ##

  * [BuildProcess](http://www.threatmind.net/secwiki/UbuntuTrinux/BuildProcess) - master document describing the build process which means how to build the initramfs, and ISO's

## Getting Involved ##
We are looking for folks to revive and contribute to this project.
  * File bugs
  * Identify new features
  * Write documentation
  * Answer questions and discuss the project - join [trinux-talk mailing list](https://lists.sourceforge.net/lists/listinfo/trinux-talk)

## Misc Wiki Pages ##
Most of these are pages on [Threatmind](http://www.threatmind.net/secwiki)

  * [ProjectActivity](http://www.threatmind.net/secwiki/UbuntuTrinux/ProjectActivity) - what is going on behind the scenes
  * [ProjectObjectives](http://www.threatmind.net/secwiki/UbuntuTrinux/ProjectObjectives) - purpose, requirements, and non-requirements
  * ProjectSources - stuff it is based upon