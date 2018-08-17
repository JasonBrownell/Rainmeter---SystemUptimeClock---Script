# Rainmeter---SystemUptimeClock---Script
# Version 2.0 #

Purpose: A Rainmeter extension to elegantly display the current system runtime with natural-language expressives.

Motivation: I created this extension for Rainmeter in order to keep track of how long my computer environment has been running, as I find it important to take the time at least once a week to manually restart Windows to keep everything running smoothly. This information has always been viewable under "Task Manager", and many other Rainmeter skins/scripts have the functionality, but I wanted something discrete and standalone from any other functions.

Development Goals: If I come back to this script, I would primarily like to refactor the expression generation in order to make the display "more intelligent". If the system has been up for "7 days | 0 hours |1 minutes | 48 seconds", I'm not sure I want to display a zero-entry for the hours. More important to me than that, I definitely do not like saying "1 minutes"....it should be singular and read "1 minute". I understand the logic conventions needed to make these distinctions in a typical OOP paradigm, but with Rainmeter, I haven't found a reasonable way to scaffold nested logic. Even things like string concatenation in Rainmeter scripting are very convoluted. I also could envision appending a message onto the widget to remind the user to restart their computer after a certain amount of time, which could be user-provided via a Settings panel (which Rainmeter does support). Changing the font-color or other effects on the day or hour transition would also make for a cool effect.

Non-Accepted Ideas: I have no interest in adding data for time intervals larger than a day or smaller than a second. Refreshing the display data and re-running logic more than once a second seems too system-taxing, and I don't see why anyone would logically want to think of their computer as running for X weeks or Y months, so I've decided to keep the extension simple with four time dimensions (day, hour, minute, and second).

If you're a Rainmeter user, please try out my latest extension! If you're not yet using Rainmeter, learn about all the cool stuff you can do with this tool at: https://www.rainmeter.net/. You're welcome to direct download, clone, or fork my script.


