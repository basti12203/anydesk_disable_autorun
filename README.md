# anydesk_disable_autorun
Systemd-Unit to disable Autostart of AnyDesk

I Do not want to start anydesk by default at startup. Normally you can mask such a unit with Systemd, when the unitfile itself is not placed within /etc/systemd.

So I ask the Maintainer to use /lib/systemd/system or one of the target inside of this directory. There was no answer within 3 months.

So i will share my solution now.
