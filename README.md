I'm not a programmer but I'd like to share my nonsense.

Just over 100 lines...

This will easily and semi-automatically mount/umount drives from the command line.<BR>
It will even semi-automatically mount/umount Luks-encrypted drives!

    mnt devXn
    mnt umnt devXn

Make an alias in your .bashrc for faster unmounting:<BR>
alias umnt\='mnt umnt'

If, for example, the command you type is:

    mnt sde1
Then it will run the command:

    mount /dev/sde1 /mnt/sde

Easy peasy!
