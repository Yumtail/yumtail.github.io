I kinda always knew that Windows *had* an event log, but I never had the curiosity to actually--you know--look at it.  Didn't seem worth the time when my goto solution for any issue with Windows is to immediately 

https://devblogs.microsoft.com/scripting/use-filterhashtable-to-filter-event-log-with-powershell/

Microsoft themselves say that piping is slow in Powershell.  This makes me wonder out loud if the same is true for Bash.  I did notice that Ubuntu has some commands like `pgrep` that at first glance seem to duplicate `ps | grep`.  There's also `pkill` which allows terminating processes by name instead of PID.