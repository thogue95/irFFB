# irFFB2022


Update: Here is a great video talking about this version - https://www.youtube.com/watch?v=lcHAX-OS58A&t=207s


There is a table embedded in irFFB.cpp with a list of road cars and their associated values for yaw and lateral factors
in calculating the force level for an understeer condition to occur.  I modified irFFB so that those values
could be set in the gui as Understeer Release Force and an Understeer Force Multiplier.  

![irFFB](https://user-images.githubusercontent.com/8271391/139556754-b960c6b3-c790-4cb3-80e7-f62fb05c6d07.png)


Those two settings need to be set for a car and track in order to get the right level.  To set them, drive the car on the track and as you go into a corner, turn the wheel AGGRESSIVELY into the turn past 90 degrees to force an understeer (push) condition.  You should
feel the wheel "break away" as you would in real life where the wheels are turned but the car keeps going straight.

Most of the time the Understeer Force Multiplier will be 2x which is default and you should target the Understeer Release Force around 30.  
With that said, these settings will depend A LOT on caster settings.  I have found some cars will need the multiplier at 1.
Once you feel it break away, keep tuning the Understeer Release Force until you like the feel but can still tell when the car enters an oversteer (push) condition.
You will find in a race that you can hold that edge and find the perfect line.

In my experience, this gives the <2NM wheels a chance at being competitive again and will make your laps more consistent.
