This automation displays the following data on an 2,66" display
* Timetable of the next school day 
* if a room is changed, its added to the line
* if a lesson is changed, the line is marked red

Its build for max of 5 hours per day, if you have more than 5 entries, you need to adjust it and make the lines smaller

Its using the following integration to get the timetable data: https://github.com/JonasJoKuJonas/homeassistant-WebUntis

You need to change the following values:
* sensor sensor.NAME_SCHULE_de_next_lesson_to_wake_up (33)
* sensor open_epaper_link.9876543210 (53)
* battery sensor name sensor.tag266_2_battery (208 + 214)
![webuntistag.jpeg](webuntistag.jpeg)