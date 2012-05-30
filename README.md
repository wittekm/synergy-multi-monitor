#Synergy-Multi-Monitor
Synergy-multi-monitor is a fork of [Synergy](http://synergy-foss.org) with better support for multiple monitors. I am mostly creating it for myself and my strange setup, but I do hope to eventually merge it back in with the main branch (if they'll have me).

##The Problem
Synergy currently has no intuitive support for the following setup.

* **Server**: has a single monitor called *ServMon*
* **Client**: has two monitors called *CliMon1* and *CliMon2*

My temporary desk is setup like this:
> [CliMon1] [ServMon] [CliMon2]

As of now, Synergy treats any multi-monitor setup on a computer as a single "screen." There is no way to tell the mouse to head over to ServMon once it hits the right edge of CliMon1; instead, it goes over to CliMon2. My aim is to fix this!

#Notes
This was originally cloned from Synergy's Google Code SVN on May 30th, 2012.
