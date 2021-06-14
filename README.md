# anydesk_disable_autorun
Systemd-Unit to disable autostart of AnyDesk

I do not want to start anydesk by default at startup. Normally you can mask such a unit with systemd, when the unitfile itself is not placed within /etc/systemd.

After a update or a reinstallation of anydesk the autostart is reenabled. So I ask the Maintainer to use /lib/systemd/system or one of the target inside of this directory. There was no answer within 3 months.

So i will share my solution now.
