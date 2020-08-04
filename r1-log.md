# #100DaysOfCode Log - Round 1 - Hubert Kowalski [Johnny_Bit]

The log of my #100DaysOfCode challenge. Started on [July 19, Sunday, 2020].

## Log

### R1D1 
Rebased https://github.com/darktable-org/darktable/pull/5520 , tried to come up with better way to handle signal debugging in https://github.com/darktable-org/darktable/pull/5433 ultimatelly failing and finally started to update https://github.com/darktable-org/darktable/pull/5124 - this will use slpashscreen IMO

### R1D2

Worked on https://github.com/darktable-org/darktable/pull/5124 for little over an hour and I think I'm defeated. I haven't found a way to show little window on closing.

### R1D3

Worked on https://github.com/darktable-org/darktable/pull/5124 - due to unforseen issues and complexity it seems that hiding main window early is the best way for now. For splashscreen opened up https://github.com/darktable-org/darktable/issues/5782
After some perl fun created PR https://github.com/darktable-org/darktable/pull/5786

### R1D4

Rebased https://github.com/darktable-org/darktable/pull/4360 and changed "user modified" icon to pen. Need help with UI/UX side of things.

### R1D5

Work on signal tracing for darktable - https://github.com/darktable-org/darktable/pull/5433 heavy stuff...
Updated https://github.com/darktable-org/darktable/pull/5520
Worked on fixover of show_icons tool - https://github.com/darktable-org/darktable/pull/5793 because some comments were missed
Learned a lot about GObject signals... still a lot of learning to do.

### R1D6

Learning about GObject signals, hardly any coding today

### R1D7

Learning GObject signals day2, I've learned about variadic macros!

### R1D8

Another day of silly macros - I think there's no way to get sensible data carried transparently with signals without intense code change :/

### R1D9

Interesting - GObject signals are connected to signal with callback + user_data, but disconnected only by callback + user_data. Which means that if you have the same callback + user_data for several signals it's enough to use 1 disconnect and it will disconnect from all. Cool!

### R1D10

Rebased signal work on current darktable master. Proably needs some work.

==

Failed ;(