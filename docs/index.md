---
title: Weather or Not
description: "The alarm clock that adjusts as your commute time changes"
layout: default
---

## Summary

_Weather or Not_ is an alarm clock designed for anyone who has to be somewhere on time. The alarm will adjust itself according to any traffic delays (caused by accidents, construction, or weather for example) to make sure you wake up with enough extra time to get where you're going by the time you need to be there.

## Intended users

* People who have longer work commutes.

    > As someone who commutes 1 hour each way for work, I don't always know when there will be construction or closures that will add an extra half hour or more to my drive. Waking up earlier when my commute will be longer would help me from being late or missing my important meetings in the morning.

* People who live in areas with erratic weather.

    > During the winter months, there's no telling if a storm that happens in the middle of the night is going to be a light dusting or plug the streets up with 2 feet of snow. If it's going to take extra time to get to school in the morning, I need to know so I can wake up with enough time to have a good breakfast before my exams.

* People planning long drives.

    > I have to drive upstate to have dinner with my in-laws tonight and need to be there by 7pm. I heard it was raining near where they are and need to know what time I should leave work so that I'm not late.


## Functionality

User will be able to:

* Input / edit the location of departure and arrival
* Select their preferred route of travel
* Select their preferred time of arrival and receive a recommended departure time
* Select the amount of time they would like between the alarm going off and their recommended time of departure
* Select from multiple alarm styles and sounds



## Persistent data

* Departure and arrival locations
* Arrival time Preferences
* Alarm style/sound preferences
* Alarm-to-departure time preferences



## Device/external services

* Android [AlarmManager API](https://developer.android.com/reference/android/app/AlarmManager)
* [Google Maps - Routes API](https://cloud.google.com/maps-platform/routes)
* Contacts information


## Stretch goals/possible enhancements

* Snooze function
* Labels for departure and arrival locations (e.g. Work, Home, Mom's, etc.)
* Receive a notification at the suggested time of departure
* Be able to label different alarms
* Be able to save different alarms for different days of the week
* Import locations from Contacts info
