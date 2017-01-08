+++
title = "FT-897D Gaming Headset Interface Ideas"
date = "2014-01-09"
categories = ["diy"]
+++

I've got a [Turtle Beach X12](http://www.turtlebeach.com/product-detail/xbox-headsets/ear-force-x12/56) gaming headset.  It comes with a digital interface for the XBox and PC.  Works on the PS3 as well.  It's a really nice headset, one of the only ones I've been comfortable wearing.  Most over ear headphones tend to smash my earlobes and that gets painful after a while.  These ones fit nicely over my ears so I don't have that problem.  When I plug them into my computer I need to plug the mic and headphone connector in, as well as the USB connection.  I assume this is for powering something or another.  

When I got my FT-897D I got the 1/4" adaptor for the headphones, and have been using a short USB extension to get power the headset.  Apparently a good number of people use computer headsets with their radios, but they only have the mic and headphone connections, not the usb one.  So I'm going to start prototyping an interface using the +5v from the FT-897D mic port (works for the FT-857D too as far as I can tell) to power the headset.  On one side will be an RJ45 connector (J1) and an audio connector (J3).  The other side will have an RJ45 connector (J2), two audio connectors (J4 and J5) and the USB connection (J7).  In addition, there will be a momentary push button somewhere on the setup to enable PTT (S1) as well as an audio jack so I can also build a handheld or foot switch PTT remote later on (J6).  Most of the schematic is designed from what I found [Here](http://charlessocci.com/2010/08/27/computer-headset-on-yaesu-ft-857d/).  

![Gaming Headset Interface Schematic]({filename}/img/X12-Headset-interface.png)

So that's the plan, any suggestions?
