# led-race
Minimalist car race with a strip of LEDs.
Connect two switches between common GND and pins 6 and 7 and one led strip ws2812 or ws2813 to  GND, + 5V and A0 to a arduino Nano

For our modifications, we used an Arduino Uno.  

The race can be 2-4 players.  Players tap the button on their controller to join the race, then a start button is used to start once everyone has joined.

The track displays random chasing and color wheel effects when the race is not active.  The DEMO be pressed to interrupt the effects before players can join the race.  This is because of the limited number of interrupt pins available on the Arduino Uno.

We're cleaning up code and adding comments to try to make it more readable.  We recently lost some of the code around sound effects and are rebuilding it as time permits
