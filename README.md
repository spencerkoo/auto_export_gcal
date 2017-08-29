# auto_export_gcal
This repo consists of scripts to automatically export your gcal and import it to another calendar. Generally meant for work calendars that do not properly sync with your personal calendar (i.e. everything shows up as "busy").

# Dependencies
PhantomJS, CasperJS

# To run
In the script, input your username and password, then navigate to the script in your directory and in the Terminal/Command Line, run "casperjs export_gcal.js"
It will automatically log you in and export your calendar in .ics format, placing the file in your Downloads folder.
