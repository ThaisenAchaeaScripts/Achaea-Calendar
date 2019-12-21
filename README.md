# Achaea-Calendar
The original and far superior calendar widget for mudlet!


## Installation Instructions

### Manual Installation
1. Download this repository as a ZIP by clicking the "Clone or download" button above
2. Unpack the ZIP somewhere...anywhere!
3. Open the mudlet packackage manager
4. Navigate to and install the "achaea-calendar.xml" script...wherever you put it...

### Automagic Installation
1. If you have a previous version installed, uninstall first via the package manager.
2. Copy the code below, paste into mudlet, press enter!

```
lua function d(_,f) if f~=getMudletHomeDir().."/achaea-calendar.xml" then return end installPackage(f) os.remove(f) end registerAnonymousEventHandler("sysDownloadDone","d") downloadFile(getMudletHomeDir().."/achaea-calendar.xml","https://thaisenachaeascripts.github.io/Achaea-Calendar/achaea-calendar.xml")
```


## Basic Usage

**ACAL** - Shows the calendar for the current year.

**ACAL #** - Shows the calendar for 1-9 years, e.g. "ACAL 2" would be two years into the future.

**ACAL CONFIG** - Shows a varity of calendar options...mostly colors


## Features

- Calendar will highlight the following:
  - Current Date
  - Orphean Serenade
  - Upcoming Events
  - Upcoming Reminders

- Hover Text!!
  - Approximate IRL date and hour for every Achaean day!
  - IRL estimates are done in LOCAL time.
  - Upcoming events and reminders.

- Automatically captures new reminders and events prior to showing calendar, no need to check them beforehand.

- Full color configuration. Don't like the defaults, no problem! Change colors using your favorite RGB combination!
