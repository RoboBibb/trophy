# Trophy
An arduino clone of a trophy my robotics team (FRC#4941) recieved at GRITS in 2014.

The final design is for 2 RGB LEDs on the top of two pegs which each have 2 red/blue bicolor leds (controlled digitally). The setup will light up in different patterns that change when the user puts their hand above the Ultrasonic Range Finder. The trophy will also have a buzzer that sounds when the user's input is received and can be disabled via a push button. There will also be a master kill/power switch that is a locking push-button. The base will be made of transparent plexiglass.

I'm testing the code on my Mega2560 but the trophy will have an arduino pro mini.

## Addendum 2017
In case you're wondering, I'm still waiting for some plexi-glass to get cut almost a year after starting this project, and thus I still don't have a completed project. I have plans for one additional light pattern, but honestly I'm happy with where the software is now.

# Here's a diagram:
```
  &     &
 |0|   |0|
 |0| u |0|
|*^#______|


& = RGB LED [PWM] (24-bit color)
0 = RGB LED [digital] (3-bit color)
u = ultrasonic range finder
* = audio-indicator led
^ = audio switch
# = master power/kill switch
```
# Here's a video:
https://youtu.be/dVyNvVf2ImU
