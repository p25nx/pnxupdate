# pnxupdate
update files for pnx-mono
Files are kept on pi or bbb as follows:
#
runtime files are in /opt/pnx-mono
#
update files are in /opt/pnxupdate
#
updater script is in /usr/local/pnxupdate/do-update.sh
#
#
#
updater runs as a cron job each night at 2:30 am, assuming you have correctly
set you system for the local time. 

it WILL kill the currently running copy of pnx-mono if a newer version is found, and restart it.
this only takes a few seconds.

