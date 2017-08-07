# Scheduler Container

This container will run scheduled shell scripts inside `scheduler/tasks/<interval>` where <interval> can be:

    - 1min
    - 5min
    - 10min
    - 15min
    - 30min
    - hourly
    - daily
    - weekly
    - monthly 

## Example

Inside `tasks/1min` you will see a example slack notification script.