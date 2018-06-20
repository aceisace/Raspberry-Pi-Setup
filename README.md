Get started quickly on raspbian with the following command:

sudo curl -sSL https://goo.gl/kS6qR9 | bash

What this command does on your system:

Expand the filesystem

Make 'sudo' require a password to improve security of the Pi

Update and upgrade the system to the latest version, replacing old files with new ones. 

Prevent the screen and wifi from sleeping if the pi is inactive to prevent connection loss

Delete Wolfram Alpha and Librefoffice to save a lot of space (~ 1 GB)

Info:
To disable power-saving mode, navigate to start>preferences>screensaver, open screensaver and select 'none' from the menu. 
Also, once finished, don't forget to reboot with:

sudo reboot
