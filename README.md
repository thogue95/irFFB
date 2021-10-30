# irFFB

There is a table embedded in irFFB.cpp with a list of road cars and their associated values for yaw and lateral factors
in calculating the force level for an oversteer condition to occur.  I modified irFFB so that those values
could be set in the gui as Oversteer Force and a Force Multiplier.  

![irFFB](https://user-images.githubusercontent.com/8271391/139541506-3a55142f-7507-4fd8-a684-a4ff3e0c2b16.png)

Those two settings need to be set for a car and track in order to get the right level.  To set them, drive the car on the track and as you go into a corner, turn the wheel AGGRESSIVELY past 90 degrees to force an oversteer condition.  You should
feel the wheel "break away" as you would in real life where the wheels are turned but the car keeps going straight.

Most of the time the multiplier will be 2 which is default and you should target the oversteer force around 30.  
With that said, these settings will depend A LOT on caster settings.  I have found some cars will need the multiplier at 1.
Once you feel it break away, keep tuning the force until you like the feel but can still tell when the car enters an oversteer condition.
You will find in a race that you can hold that edge and find the perfect line.
In my experience, this gives the <2NM wheels a chance at being competitive again and will make your laps more consistent.
