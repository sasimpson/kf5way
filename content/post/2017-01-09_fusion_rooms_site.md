+++
date = "2017-01-08T09:41:08-06:00"
title = "Fusion Rooms Tool"
categories = ["tools"]
+++

When I started using the Yaesu System Fusion stuff, I really wanted to try Wires-X.  I upgraded my FTM-100DR to an FTM-400XDR as my mobile and put the FTM-100 on base station duty.  I really like using APRS when I'm out and about, so the dual receivers of the 400 was better for that.  One of our local repeaters, hosted by Greg K4HBM, has a Wires-X module on it, allowing me to connect it to any number of *rooms* or *nodes*.  A *node* is the actual radio, whether it be a radio or a repeater, with a Wires-X module.  A *room* is a logical grouping of nodes that are connected.  Think of it like a chat room versus a direct connection.  

Well Yaesu curates this system, which is a point of contention for me, but they also provide a listing.  The listing isn't very great, you can see it [here](https://www.yaesu.com/jp/en/wires-x/id/active_room.php).  So I've built an app that allows you to see which rooms exist for which country, and sorted by number of connections.  It is mobile friendly so you can view it on your phone.  One major advantage of using it this way is that you get the DTMF ID very clearly and you can just dial that in with your keypad.  Just hit #&lt;room dtmfid&gt;# and you should get connected.  To disconnect you just dial #99999#.  

You can view the site at [fusion.ke5eo.com](http://fusion.ke5eo.com) and it is mobile friendly as well.  

I'm going to try and add links to websites if people have them, as suggested by Stuart M0SGS.  If you have any other suggestions, don't hesitate to reach out!

### Main Page View
![Fusion App](/img/fusionapp1.png)
### Country View
![Fusion App](/img/fusionapp2.png)
### Room View
![Fusion App](/img/fusionapp3.png)