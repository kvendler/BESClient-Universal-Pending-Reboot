# BESClient-Universal-Pending-Reboot
Version 1.0.1

This project includes the following content:

1. A BigFix Analysis (Universal Pending Reboot Status.bes) that displays the pending reboot status of both Windows and Linux devices. For Windows devices, the Pending Restart flag is used for detection. For Linux devices, the presence or absence of /var/run/rebbot-required is used.
2. A Fixlet (Execute Required Reboot With Delay [Windows].bes) to restart Windows devices with a three minute delay.
3. A Fixlet (Execute Required Reboot With Delay [Linux].bes) to restart Linux devices with a three minute delay.
