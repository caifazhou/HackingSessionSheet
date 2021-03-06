# System management

### Exercise 1: Power on/off

a) Try to put your computer into suspend, and wake it back up.
```
    systemctl suspend
```

b)
```
    shutdown 10
    shutdown -c
```

c) Reboot your computer from the command line.
```
    reboot
```

### Exercise 2: Space left on disk

a) Find out what size (in MB) the exercise directory has.
```
    du -sh HackingSessionExercises
```

b) Find out how much space is used by your root directory `/`.
```
    df -h /
```

### Exercise 3: User management

a) Add a new user called `ExerciseUser`.
```
    sudo useradd exercise_user
```

b) Add a new group called `exercise_group`.
```
    sudo groupadd exercise_group
```

c) Add your new user to the new group.
```
    sudo gpasswd -a exercise_user exercise_group
```

d) Remove the user and the group again.
```
    sudo userdel exercise_user
    sudo groupdel exercise_group
```
