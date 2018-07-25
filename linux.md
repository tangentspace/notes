## Utilities

### run-one
I often need to repeat a command until it succeeds in a one-liner. The `run-one` package in Ubuntu repositories
contains a few utilities, including `run-one-until-success` which often does the trick! Here's the
man page:
* http://manpages.ubuntu.com/manpages/bionic/man1/run-one.1.html

#### Example: Wait for NTP synchronization to complete
```
run-one-until-success /bin/bash -c 'timedatectl status |grep -q "NTP synchronized: yes"'
```

#### Limitations
This tool is a simple bash script, and the retry timing is hardcoded. It starts off sleeping 0 seconds between
retries, then increments the sleep by 1 second for every 10 failed attempts, up to a maximum of 60 seconds.

Logging is also hardcoded. It logs using the logger command, so messages end up in /var/log/syslog by default.
