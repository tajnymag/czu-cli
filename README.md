# czu-cli

As simple cli as possible for Czech University of Life Sciences Prague.

Currently supports only extraction and conversion of student's timetable.

## Installation
```bash
yarn global add czu-cli

# or

npm install -g czu-cli
```

## Run
```bash
# help
czu-cli --help

# print current timetable as iCalendar
czu-cli timetable --username "xlukm014" --password "hunter2" --format ics

# save it to a file called calendar.ics
czu-cli timetable -u "xlukm014" -p "hunter2" --format ics -o calendar.ics
```

## Upcoming features
* easier installation (precompiled binary)
* uemp support
* searching for empty classroom
* monitoring of timetable changes

## Goals
* provide quick and secure access to your UIS
* fix errors caused by incorrectly exported iCalendar by UIS
* cover all desired features by request of other students

## Contributing
1. Create a Github account
2. Fork this repo
3. Download your forked version to your computer
4. Change/Add the stuff you want
5. Push/Sync your changes back to your repository
6. Submit a pull-request back into this repo