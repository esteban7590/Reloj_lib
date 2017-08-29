# Reloj_lib

Library for setting up time and date, and alarms in a DS3231.

Function void set_time() takes the compilation time and sets it to the RTC (~30s delay).

Function int get_time_hours() retunrs an intenger containing the hour of the actual time.

Function int get_time_minutes() retunrs an intenger containing the minutes of the actual time.

void set_alarm(int hour, int minutes) sets up a new alarm at the time indicated every day.

Function void reset_alarm() resets the SQW pin of the DS3231 and the flags created for interrupts.

Function void printDateTime() prints the date and time to the serial port at 9600.
