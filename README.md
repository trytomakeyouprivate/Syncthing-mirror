# Syncthing-mirror
Explaining a setup how to sync between two Laptops

Syncthing is a great tool, it works locally or over the internet and allows secure and serverless synchronisation of data.

You dont need a cloud to have your stuff everywhere you want. And if thats at least 2 devices, the chances of losing it is already really low.

## Best practices
Try not to sync too many folders and prefer to maybe restructure your files. If you often need to change setups, this may help.

## PC to PC
My setup has a KDE desktop and nearly exclusively Flatpak apps. I use [SyncThingy](https://flathub.org/apps/details/com.github.zocker_160.SyncThingy), which autostarts on login and works great.

1. Use an app like [ClipQR](https://flathub.org/apps/details/ch.imatt.ClipQR) and scan the QR Code of one Syncthing machine ("Show ID") with the other machine
2. Add the machine on the other laptop using the copied ID
3. Delete the standard folder if you dont need it
4. Create a new synced folder, it uses the home directory, remov the created foldername from random letters
5. Add your other machine to the "shared" list
6. Before adding it, enable "ignore patterns" and create
7. Enter the ignore pattern in the text field
8. Go to your other machine and add the folder, also choose your home directory

Match the settings how you want them. For example you may want basic apps to be the same everywhere, but you only do Gaming or Video editing on a PC, so you exclude these apps from syncing.
