This is a simple script that checks if you have a currently running Harvest timer.
If there isn’t one, it will show a notification and activate Harvest.

Inspired by http://dafacto.com/2012/how-to-never-forget-to-enable-your-time-tracking-timer/

## Prerequisites
- requests python library (`pip install requests`)
- [Keyboard Maestro](keyboardmaestro.com)

## Steps
1. Clone/download this repo to somewhere
2. Import the included macro into Keyboard Maestro
3. Modify the script action inside the macro with your script path, Harvest account ID and API token.
To obtain a token go here: https://id.getharvest.com/developers
4. Set the notification hours and days that fit your schedule.

Enjoy!
