# BESClient-Universal-Pending-Reboot

This project includes the following content:

1. A BigFix Analysis that displays the pending reboot status of both Windows and Linux devices. For Windows devices, the Pending Restart flag is used for detection. For Linux devices, the presence or absence of /var/run/rebbot-required is used.
2. A Fixlet to Restart Windows devices with a three minute delay.
3. A Fixlet to Restart Linux devices with a three minute delay.
