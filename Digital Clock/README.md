<h1>Digital Clock Project</h1>


The project is based on the principle of 2 stage counter operation, based on synchronous
cascading. The idea is to display clock pulses count from 0 to 59, representing a 60 second time
interval. This is done by using a 555 Timer IC connected in astable mode to produce the clock
pulses of 1 second interval each. While the first counter counts from 0 to 9, the second counter
starts its counting operation every time the count value of first counter reaches 9. The counter ICs
connected in cascading format and each counter output is connected to BCD to 7 segment
decoder used to drive the 7 segment displays. When the value displayed is 59, the counters restart
from 00.
<h2>Bonus part:</h2>
Make 4 digits, two of them for the seconds, and the other two for displaying minutes. When you
reach 59, in the next clock cycle the minutes are augmented by one and the seconds resets to 0,
and restarts counting.
