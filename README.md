# Introduction #

This is an easy sync script to help you sync files to multi hosts. The
script is actually a wrapper of `rsync` command, so please make sure
you have install `rsync` at first. You can use `.ezsync.conf` to
specify the behaviour of the script. `ezsync` will search it in the
current directory firstly, then `$HOME`, and at last the directory of
the script. Thus you can have a specific config file for your current
workspace and keep a global config file for daily use.


