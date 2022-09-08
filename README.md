# irFFB2022

Update Sept 8, 2022:  irFFB2022 Version 2
irFFB2022 Version 2 adds a SimHub Connector capability along with the SimHub Connector Plugin and 2 SimHub overlays to install into your SimHub environment to bring irFFB2022 controls into your car while you are on the track.  No more guessing what irFFB is doing, whether or not it is running correctly and now you can dial your force feedback to the perfect levels while racing. You GET control!!!

![irFFB2022 Overlay no data](https://user-images.githubusercontent.com/8271391/189239935-31e69f93-8367-40de-b0c4-ab66251cda01.png)

![irFFB2022 Status green](https://user-images.githubusercontent.com/8271391/189239958-9b7ac50e-cc55-4860-8a8f-4de308d41e94.png)

Find the irFFB2022v2 document for instructions and details on how to make it work.  For those that don't read...

TL;DR (Too long, Did not read)
1.	Copy irFFB2022.exe over the previous version
2.	Install Toms.irFFB2022Connector.dll into the SimHub directory
3.	Install the two overlays into the DashTemplate subdirectory
4.	Bind Keys
5.	Setup screen with overlays
6.	When in car on track, press the button/key that Max Force was mapped to several times to activate the connector 

Files to download:
irFFB2022.exe
Toms.irFFB2022Connector.dll
Toms.irFFB Dash.zip
Toms.irFFB Status.zip
irFFB2022.pdf - How to guide



-----------------------

irFFB2022 is an update to irFFB that is found on the nlp80/irffb github repository that was last updated sometime in 2020.  The irFFB2022 version keeps the core internals as in the original version of irFFB, but simplifies the configuration and controls of irFFB so that users can optimize their settings for their car and track.   The key objective was to make irFFB easy to understand and easy to use. As a result, you will find it much easier to optimize your FFB experience in iRacing and achieve most consistent lap times over a longer period of time.  For those NextGen Cup racers, you may even find yourself recovering from those dreaded snap spins. It was those snap spins that got me to come back and take a new look at irFFB.

New Features:

•	Easy to Understand Modes

•	Automatic -360 Smoothing Mode for a blend of Low Latency and Telemetry Enhancements

•	Previous “Offsets” were modified and presented as “Effect Timings” in a simple single control slider

•	SoP renamed to Oversteer to make it easier to understand

•	Understeer enabled for all cars and easily configured with a slider

•	Car and Track combinations are saved together to reduce configure a car for a track

![Screen Shot 2022-08-08 at 5 40 21 AM](https://user-images.githubusercontent.com/8271391/183484997-ffed5e9e-df1c-43fa-b0d0-75975f3f113c.png)
![Screen Shot 2022-08-08 at 5 40 34 AM](https://user-images.githubusercontent.com/8271391/183485016-a027c9c7-e594-4e1b-8be1-356b5acd3c3d.png)

Two guides are posted:

The TL;DR (aka Short Guide) and the Long Guide.  I attached those so you can use them as reference.

I would like to stress that you run irFFB2022 before you launch into a sim session.  It really does not like to start after the session.  Maybe a fix for that at a later date.  If you are still running irFFB, the same suggestion applies.
