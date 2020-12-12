# alarmclock
alarm clock python project

Hello, this is the README document for a COVID-19 - daily-briefing alarm clock,
Author: Artur Marek Kapitanczyk
License: MIT license


Python 3 is required as a minimum version to run this program.
The program runs on the address: 127.0.0.1:5000 (copy and paste in browser once program is run)
Before you start up the program, there are some must-do changes you need to do to the config.json file in order for the program to work.

You need to go to  (https://openweathermap.org) to get a weather API key and to (https://newsapi.org/) to get a news API key

Paste these API keys into appropriate places (should tell you where to paste) in the config.json file.

If you do these basic settings, you should be able to run the program, however there are a few other optional changes you can do to the config.json file to enhance your experience:
1. You can change the values in the covid-API-setup to change where the covid-cases information comes from (by default this is Devon, UK)
2. You can change the values in the weather-API-setup to change where weather update information comes from (by default this is Exeter, UK)
3. You can change the values in the daily-briefing-precise-time to change at what hour and minute the daily briefing will show every day (by default this is 12:00 - midday)

INSTALLATION REQUIERMENTS
pip install pyttsx3
pip install uk-covid19
pip install flask
pip install datetime
pip install sched
pip install time
pip install logging
pip install requests
pip install json
