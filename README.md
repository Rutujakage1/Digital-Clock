# Digital-Clock
## Design and Implement digital clock to display time in hours, minutes and seconds

### Introduction:
A digital clock or digital watch is one in which the hours, minutes, and seconds are indicated by digits, rather than by hands on a dial as in analogue clock.Digital clocks display have hour sequence option as 24-hour format and 12-hour format. Designed here is a 12-hour format clock.

The easiest approach of implementing the digital clock is using 7490 decade counter. On our digital clock circuit. We will use divide-by 10, divide-by 6 and divide-by 2. This circuit design is not adjustable so its needed to start the clock exactly 00:00 or 12am.

### Methodology:
Its known that 60 seconds equal to 1 minute and 60 minutes equal to 1 hour. Hence the minute section is divided by second section and hour section by minute section. Each of the minute and second section has been designed to give a count from 00 to 59 after which it resets.An hour section to give a count 00 to 11 hours after which it resets to 00. 
The entire implementation has 3 sections:<br />
1.Second section <br />
2.Minute section<br />
3.Hour section<br />

Assembling these three sections gives the Digital Clock. Here in the implementation:<br />
SECONDS' ones, MINUTES' ones and HOURS' ones are divide by 10.<br />
SECONDS' tens and MINUTES' tens are divide by 6. <br />
HOURS' ones is divide by 2.<br />

### Detailed Block diagram:

<p align="center">
  <img width="600" height="450" src="https://user-images.githubusercontent.com/69888083/129455507-6e8811c0-87f4-49bf-9d85-fea47e12be27.png">
</p>

### Simulation Results:
The design is simulated in Proteus 8 professional before implementing on the hardware. 
<p align="center">
  <img width="600" height="450" src="https://user-images.githubusercontent.com/69888083/129455821-49f96caa-1630-453a-8507-ac5d3fb66b61.png">
</p>

### Final Results:
The output of the HOURS' tens digit is connected to an AND gate that will reset the counter to 00 when 12 is counted. The clock source will depend on the designer.

<p align="center">
  <img width="600" height="250" src="https://user-images.githubusercontent.com/69888083/92466625-01a01400-f1ee-11ea-86c7-dbf2bef81973.png"
  </p>   
  <p align="center">
  <img width="600" height="450" src="https://user-images.githubusercontent.com/69888083/92466666-15e41100-f1ee-11ea-8c75-2efe9cb305bd.png">
</p>

The circuit is purely designed with the  basic knowledge on sequential circuit designing  and hence   digital 12Hr clock is  successfully implemented which is displayed on the  7 segments.

