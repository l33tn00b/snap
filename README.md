# snap
wtf snap debug

# view logs of snap applications

`journalctl -f -u snap.mosquitto*`

# multiple instances of a snap  
As of 08/2024 and per https://snapcraft.io/docs/parallel-installs  
- `sudo snap set system experimental.parallel-instances=true`
- Maybe reboot
- 
