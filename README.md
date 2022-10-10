Start
IF temperature <18c THEN
SEND "Cold, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
ELSE
IF tempersture >21c THEN
SEND "Perfect" TO DISPLAY
ELSE
SEND "No!,the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
END IF
END IF
