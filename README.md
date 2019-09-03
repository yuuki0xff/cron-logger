# cron-logger

The cron-logger is wrapper script for cron jobs. It intends to reduces email
from crond.  By default, crond sends the output to your mailbox.  This
behavior is VERY BAD.  You will be exhausted and will no longer read emails
from crond.

The cron-logger sends all outupt (stdout and stderr) to system log.  If
command failed, cron-logger also send the output to crond.


License: Apache 2.0  
Site: https://github.com/yuuki0xff/cron-logger
