## System management

### Power on/off

You can use the shell to do various sytem management tasks. To shut down, reboot,
or put your computer in suspend mode, you can use `reboot`, `poweroff`, or
`systemctl suspend` respectively. (You might need to use `sudo` on your system)

a) Try to put your computer into suspend, and wake it back up.
b) Reboot your computer from the command line.

### Space left on disk

Useful commands: `df`, `dh`

a) Find out what size (in MB) the exercise directory has.
b) Find out how much space is used by your root directory `/`.

### User management

Useful commands: `useradd`, `userdel`, `groupadd`, `groupdel`, `gpasswd`, `passwd`

a) Add a new user called `ExerciseUser`.
b) Add a new group called `ExerciseGroup`.
c) Add your new user to the new group.
d) Remove the user and the group again.

If you are confused by `gpasswd` and `passwd`, consider the following hint:
One of them is used to set the password for a user, the other is used to add
a user to a group.