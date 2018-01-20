To quickly get started on raspbian, I've compiled a few useful commands.These will help keeping up to date and freeing a bit of space.

Features:

update and upgrade raspbian

update the firmware to the latest version

install xscreensaver (this will prevent wifi being turned off to save power)

completely remove wolfram-alpha and libreoffice (can save up to 1 GB of space)

function to make sudo require a password each time (improves security)



To get started, typein this command in LX-Terminal:
curl -sSL https://goo.gl/kS6qR9 | bash

Depending on the connection speed, this command might take a while (<10mins)

The last command will allow you to make sudo require a password. To do so, edit the opened file which looks like this:

pi ALL=(ALL) NOPASSWD: ALL

to this:

pi ALL=(ALL) PASSWD: ALL

Save the file by pressing Crtl and X at the same time. Then, press Y to save the changes and enter to confirm.

To disable power-saving mode, navigate to start>preferences>screensaver, open screensaver and select 'none' from the menu. 
