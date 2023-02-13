Project Description
============

Cinnamon is a Linux desktop that provides advanced innovative features and a traditional user experience.

The desktop layout is similar to Gnome 2 with underlying technology forked from Gnome Shell.
Cinnamon makes users feel at home with an easy-to-use and comfortable desktop experience. These
experiences come in many forms and include but arent limited to:
Panels, hot corners, and menus
Cinnamon Control Center
Cinnamon Desktop
MDM Display Manager
Cinnamon Menus
Nemo
Cinnamon Screensavor
Cinnamon Session
Cinnamon Spices and Translations

How to Install and Run
============
You will need Docker Compose installed on your system, we recommend having a Linux workstation or shell.
You can follow the steps listed here:https://docs.docker.com/compose/install/linux/

Install all the cinnamon dependencies:
apt-get update

apt-get install dpkg-dev

sudo apt-get build-dep cinnamon cinnamon-control-center cinnamon-desktop cinnamon-menus cinnamon-screensaver cinnamon-session cinnamon-settings-daemon cinnamon-translations cjs muffin nemo

CD into cinnamon/.github/workflows/
Run docker-compose -f build.yml up
Reference to this build process can be found here:
https://github.com/linuxmint/cinnamon/actions/runs/3919992582/jobs/6701340204

How to Use the Project
============
This project can be used the same way any linux distribution can be used, an installation for
your Linux machine or a means to develop on Linux and expand its features. You can also experiment
with the added features to see what kind of changes you would like to see next.

Coding Standards
============
The coding style this project uses is consistent with the Java Coding Standards found on the Oracle webpage:
4 space indentation, camel casing for variables and class names, wrapping lines, comment formation,
declaration statements, and statements, are only a few practices adopted from the guide.Please see the full
documentation on the Oracle website for reference:

https://www.oracle.com/technetwork/java/codeconventions-150003.pdf

Contributing
============
Cinnamon is on GitHub at https://github.com/linuxmint/cinnamon.

Note that some issues may not be with Cinnamon itself. For a list of related components, please see

https://projects.linuxmint.com/cinnamon/.

Additionally, linux mint has a chat server setup for the developer community:

#linuxmint-dev on irc.spotchat.org

License
=======
Cinnamon is distributed under the terms of the GNU General Public License,
version 2 or later. See the COPYING file for details.
