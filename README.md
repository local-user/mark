#mark
A tool for marking/tracking directories.

##installation
- `git clone https://github.com/local-user/mark.git`
- `cd mark.git`
- `bin/mark`

##extra
Add the following line to '.bashrc' to change directory on launch to `mark --latest`
- `hash mark 2>/dev/null && [ ! -z "$(mark --latest)" ] && cd "$(mark --latest)"`
Note the above assumes 'mark' exists in your PATH


##usage
- `mark`
- `mark --history`
- `mark --latest`
- `mark --reset`
