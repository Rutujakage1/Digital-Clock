# Digital-Clock
Digital Circuits Course Project
A digital clock or digital watch is one in which the hours, minutes, and seconds are indicated by digits, rather than by hands on a dial as in analogue clock.Digital clocks display have hour sequence option as 24-hour format and 12-hour format. Designed here is a 12-hour format clock.

The easiest approach of implementing the digital clock is using 7490 decade counter. On our digital clock circuit. We will use divide-by 10, divide-by 6 and divide-by 2. This circuit design is not adjustable so its needed to start the clock exactly 00:00 or 12am.

Its known that 60 seconds equal to 1 minute and 60 minutes equal to 1 hour. Hence the minute section is divided by second section and hour section by minute section. Each of the minute and second section has been designed to give a count from 00 to 59 after which it resets.An hour section to give a count 00 to 11 hours after which it resets to 00. The entire has 3 sections:


