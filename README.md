#mark
A tool for marking/tracking directories.

##installation
- `git clone https://github.com/local-user/mark.git`
- `cd mark.git`
- `bin/mark`

##installation - extra
Add the following line to '.bashrc' to change directory on launch to `mark --latest`
- `hash mark 2>/dev/null && [ ! -z "$(mark --latest)" ] && cd $(mark --latest)`

##usage
- `mark`
- `mark --history`
- `mark --latest`
- `mark --reset`
