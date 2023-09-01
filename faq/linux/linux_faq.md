#### Question: User limit of inotify watches reached

adding this line to the end of file `/etc/sysctl.conf`

```txt
fs.inotify.max_user_watches=100000
```

then run command `sysctl -p`

>[more info](https://stackoverflow.com/questions/47075661/error-user-limit-of-inotify-watches-reached-extreact-build)

#### Question: Take the screeshot image is black

editing the file `/etc/gdm3/custom.conf`, make sure the below line is uncomment

```txt
WaylandEnable=false
```

then reboot the system

> [more info](https://answers.launchpad.net/sikuli/+question/703405)