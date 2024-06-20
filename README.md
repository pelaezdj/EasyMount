I'm not a programmer but I'd like to share my nonsense.

Just over 100 lines...

This will easily and semi-automatically mount or umount drives from the command line.
<BR>It will even semi-automatically mount or umount Luks-encrypted drives!

    mnt sdx
    mnt umnt sdx

Make an alias in your .bashrc for faster unmounting:

    alias umnt='mnt umnt'

<BR>if, for example, the command you type is:

    mnt sde2
then it will run the command:

    mount /dev/sde2 /mnt/sde2

<BR>if, for example, the command you type is:

    mnt sdb
then it will run the command:

    mount /dev/sdb1 /mnt/sdb

<BR>It also automatically uses "sudo" when necessary.

Easy peasy!
