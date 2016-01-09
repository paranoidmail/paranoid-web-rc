@PARANOID Project with Roundcube Webmail 
=================
[paranoid.EMAIL](http://paranoid.email) OpenPGP-compliant encrypted email service, aimed to make the whole process of encrypted communication much easier than it exists today

[roundcube.net](http://roundcube.net) browser-based multilingual IMAP client with an application-like user interface

[paranoidpi.com](http://paranoidpi.com) OpenPGP-compliant raspbian project designed to use inside NAT network at home / office / local network. 

INTRODUCTION
------------
Return the privacy to day-to-day email communication and make it as popular as possible. Make it de-facto standard. Private conversations are not for everybody and encryption makes the body of your private email unreadable on its transit for any third party. Even if the message created for you is not encrypted (for any reason), we'll make this job for you, so your whole Inbox will be readable by you and by you only (unless your private key(s) are compromised).

What is @PARANOID ?
------------
ParanoidMail is the OpenPGP-compliant encrypted email service, aimed to make the whole process of encrypted communication much easier than it exists today at the same time minimising the inevitable security trade-offs.

There is no reason to re-invent the bicycle regarding encryption standards, OpenPGP (Pretty Good Privacy) makes its job really well and with proper key size its (still) unbreakable. Unfortunately, PGP key management solutions from their very beginning till today are still tools developed 'by geeks and for geeks'. Our mission is to revamp it as 'by geeks, but for people'.

What is the @PARANOID Pi?
------------
PARANOID Pi is a pre-configured Raspberry PI image which designed to read and write OpenPGP encrypted emails from the local / home / office network. RPi image consist of @PARANOID scripts, Roundcube webmail 1.2 and Enigma OpenPGP plugin. Current version of the bundle allows to use your private key to decrypt emails and encrypt emails with public keys within @PARANOID mailbox.

INSTALLATION
------------
There are two option for the moment:
1. Download pre build RPi image and burn it on SD/MicroSD card.
2. To use the step by step script to deploy the @PARANOID Pi Bundle on existing RPi Raspbian. 

DOWNLOAD 
------------
SD/MicroSD @PARANOID Pi image can be downloaded here: [paranoid.EMAIL](http://paranoid.email/paranoidpi)
Minimal SD/Micro SD card size is 2GB, if card is bigger then 2GB boot script will automatically extend it to maximum size of the card. The image is compatible with Raspberry Pi 2 Model B and Raspberry Pi 1 Model B+

LICENSE
-------
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License (**with exceptions
for skins & plugins**) as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see [www.gnu.org/licenses/][gpl].

CONTACT
-------

You're always welcome to send a message to the project admin:
support(at)paranoid(dot)email


[pear]:         http://pear.php.net
[iloha]:        http://sourceforge.net/projects/ilohamail/
[tinymce]:      http://www.tinymce.com/
[googiespell]:  http://orangoo.com/labs/GoogieSpell/
[washtml]:      http://www.ubixis.com/washtml/
[kmgerich]:     http://kmgerich.com/
[gpl]:          http://www.gnu.org/licenses/
[license]:      http://roundcube.net/license
[contrib]:      http://roundcube.net/contribute
[support]:      http://roundcube.net/support
[tracreport]:   http://trac.roundcube.net/wiki/Howto_ReportIssues

