# SDFPAU
Steam Deck Flatpak Auto Update - Run the Flatpak update command whenever you log into desktop mode!

This simply adds a script to KDE to run the Flatpak update command at login, however this only works in desktop mode. Simply go into desktop mode and wait for the notification to appear that it has finished running. This does not mean that any updates have been applied, only that it has ran, if you lack internet connection or there are no updates, you will still get the message. You can check in the Discover store to verify that there are no updates.

Installation is automated with this one-liner, you can copy and paste the following in the terminal:

`wget https://raw.githubusercontent.com/brendenhoffman/SDFPAU/main/install.sh && sh install.sh`
