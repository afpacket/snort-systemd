# snort-systemd
###############
systemd unit file for Snort (tested on EL7)

## Prerequisites 

`touch /etc/tmpfiles.d/snort.conf`

`echo "d /var/run/snort 0775 root snort" > /etc/tmpfiles.d/snort.conf`
