I'm not a programmer but I'd like to share my nonsense.

This will easily and semi-automatically mount/umount drives from the command line.<BR>
It will even semi-automatically mount/umount Luks-encrypted drives!

mnt devX<BR>
mnt umnt devX

Make an alias in your .bashrc for faster unmounting:<BR>
alias umnt\='mnt umnt'

Easy peasy!
