I'm not a programmer but I'd like to share my nonsense.

This will easily and semi-automatically mount drives from the command line.<BR>
It will even semi-automatically mount Luks-encrypted drives!

mnt DeviceName
mnt umnt DeviceName

Make an alias in your .bashrc for faster unmounting:
"alias umnt='mnt umnt'"

Easy peasy!
