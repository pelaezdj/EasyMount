I'm not a programmer but I'd like to share my nonsense.

Just over 100 lines...

This will easily and semi-automatically mount/umount drives from the command line.<BR>
It will even semi-automatically mount/umount Luks-encrypted drives!

    mnt sdx
    mnt umnt sdx

Make an alias in your .bashrc for faster unmounting:

    alias umnt='mnt umnt'

If, for example, the command you type is:

    mnt sde2
Then it will run the command:

    mount /dev/sde2 /mnt/sde2

If, for example, the command you type is:

    mnt sdb
Then it will run the command:

    mount /dev/sdb1 /mnt/sdb

It also automatically recognizes if "sudo" is necessary.

Easy peasy!
