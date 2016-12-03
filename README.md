#mark
A tool for marking/tracking directories.

##installation
- `git clone https://github.com/local-user/mark.git`
- `cd mark.git`
- `bin/mark`

##extra - latest - cd - lcd
- `alias mark-lcd='echo = $(mark --latest) && cd $(mark --latest)'`

##extra - latest - cd - auto
Add the following line to '.bashrc' to change directory on launch to `mark --latest`
`hash mark 2>/dev/null && [ ! -z "$(mark --latest)" ] && cd "$(mark --latest)"`
Note the above assumes 'mark' exists in your PATH

##usage
- `mark`
- `mark --history`
- `mark --latest`
- `mark --reset`
