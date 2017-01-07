+++
date = "2016-12-29T15:45:05-06:00"
title = "frustrating software choices"
draft = true

+++

**NOTE**  This is a request for Windows 10, please don't say anything about Linux.  No disrespect.  I'm a fan, I just don't want to dual boot my home desktop, as sometimes while I do other things on Windows (games, work, etc), I like to leave the radio on processing stuff like PSK or JT65. 

**Background** 

I've been using HRD since I had my first HF radio, a Yaesu FT-897D, now I have a KX3 with KXPA100.  I'm trying to figure out how to use something other than HRD, for obvious reasons.  My issue is that everything else is really janky.  I like to operate just about every mode, CW, SSB, Data (PSK and JT65 primarily).  Mostly data and CW as I'm still learning to copy.  My previous setup was HRD Suite, which gave me access to just about everything except JT and CWSkimmer.  

**Current Setup**
* HRD 6.3 latest.  Logging, some digital, CAT control
* WSJT-X 1.7 latest.  JT modes, uses HRD for CAT
* JTAlert latest.  Allows me to log from WSJT-X to HRD LogBook.
* CWSkimmer latest. Allows me to monitor and skim CW out there.  Only thing that doesn't integrate with HRD LogBook/CAT Control

**Problem 1: CAT Control**

It seems like there are so many options and none of them line up :(

|App|Direct|hamlib|rigctl|omnirig| DXL Commander|HRD|
|-|-|-|-|-|-|-|
|WSJT-X|yes|yes, net rigctl|no|no|yes|yes|
|CWSkimmer|no|no|no|yes|no|no|
|FLDigi|no|yes|yes|no|no|no|
|WinWarbler|no|no|no|no|yes|no|
|DM780|no|no|no|no|no|yes|

* *WSJT-X*: can use HRD, DX Lab Suite Commander, hamlib net rigctl (don't necessarily know what this is), and direct to the rig
* *CWSkimmer*: can use OmniRig, which only has direct to my radio. 
* *FLDigi* can use direct via RigCat, FLRig, or hamlib, plus XML-RPC.

**Problem 2: Logging**

The aforementioned programs only work with certain logging.  I won't even bother with CWSkimmer, i don't mind doing that manually.

* *WSJT-X*: using JTAlert I can log through HRD 5-6