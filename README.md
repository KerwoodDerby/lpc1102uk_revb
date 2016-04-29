# lpc1102uk_revb

## A slight improvement on richardeoin's OSHPark design.
That design can be found [here](https://oshpark.com/shared_projects/Tokc44bz).

##My revision

I wanted access to the interior pins, so I tweaked the WLCSP16 pattern to give me a little room
for a 5 mil trace. This exceeds the design rules for OSHPark 2-layer boards, but I can claim
success, having just gotten my [boards](https://oshpark.com/shared_projects/Yf2WkhM2) back and
successfully programmed my diminutive LPC1102UK!

Only the XTALIN pin is not brought out, since I thought that wasn't critical for doing
exploratory programming. I made other changes, mostly the size of the other LEDs and resistors.
