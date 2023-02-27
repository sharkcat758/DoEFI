DoEFI
==================
This command makes it easy to mount the EFI right away when installing Opencore or Clover to run Hackintosh for example.
well... Im so sorry maybe the construction can be very simple and sloppy.

## How to install and use DoEFI

1. First,Download latest version DoEFI from  [This Link](https://github.com/sharkcat758/DoEFI/releases) . 
After downloading, you can run it after changing permissions using the 'chmod' command.

Up until the previous version, we had an installation wizard, but it was optimized for zsh only, various bugs occurred including problems with administrative privileges, and we did not feel the need to have a complicated installation process for a very crude piece of software, and we felt it was against the spirit of open source. Therefore, it was discontinued.

Therefore, after downloading, you may pass through PATH or modify the file, but please refrain from secondary distribution after modification.

2. Type `doefi [OPTON]`.

   Mount EFI > `doefi -m`
   Unmount EFI > `doefi -u`
   Help DoEFI > `doefi -h`
   This command is need " Root (su) "




## Change log

#### 2.0

Eliminated installation.

#### 1.1

1.1
- rebuild



#### 1.0

release 1.0( ß )
- first release.  Includes basic options. We plan to implement commands for Hackintosh in the future.


