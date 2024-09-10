---
author: "zuri-zel"
title: "cross-platform computer interface"
date: "2024-09-09"
description: "creating a consistent cross-platform computer interface: a personal journey"
tags: ["window manager", "io devices", "multi-os"]
---

in today's world, many of us find ourselves switching between multiple devices which have multiple different operating systems throughout our workday. the constant shift leads to productivity loss and unnecesary cognitive load as we adapt to different interfaces. in this article i share with you how i approached the creation of a consistent interface between me and the machines i work with(linux and macos), with a focus on consistency.

## motivation

after several years of dealing with rsi(carpal tunnel), the benefits of using the right io devices and  a comfortable and cosistent way to interface with my machines go far beyond ergonomics. the goal became to create a set up that would feel familiar and comfortable regardless of the os i was currently using, reducing the friction when changing machines and trying to enhance productivity.

## my components for a consistent interface

### tiling window managers

the first thing to tackle is how you interface with the different programs in your system, nowadays we use guis everywhere and as such every single program usually creates a window in your operative system. you need to eficiently navigate your programs, launch them and organize them on your screen. most of the time this is achieved by using the mouse but given the rsi is better if i keep my hands close to the keyboard. many oses have some keyboard shortcuts but most are designed to use a pointer device. as such tiling window manager are usually though with the keyboard as the main interface to completely control the windows.

my first introduction to them was with pop os, it managed to include all the features needed to organize and navigate the ammount of windows i tend to have open (3-4 browser windows, a terminal, a text editor, a multimedia player, and the occasionaly pdf). the pop shell allowed me to float, stack, move, and switch windows easily with my keyboard. this was the start of it.

things became difficult with mac os. there has been several attempts to create a good tiling window manager, but some were real cumbersome to install, required to modify system files or straight up didn't work. for a long time i settled with the window manager that raycast includes that allow you to move windows to common snap points and used a shortcut to change windows by searching the window name, i was using mostly the keyboard but it felt slow and cumbersome.
i though there was no solution until a few weeks back a name started to appear both in youtube and other forums, aerospace, a new contender in the tiling window manager scene for mac, so i decided to give it a chanced.

to my surprise i was able to do all the same operations i usually do in the pop shell with ease, although the keyboard shortcuts were completely different. this will need to be addresed


- linux: pop shell (default in pop os)
- macos: aerospace

### launching apps

interacting with windows was solved, now i have to launch them, again in pop os you have a handy dandy launch bar to search and select your apps. mac has spotlight but is not nearly as useful, i already solved this problem before and i mentioned the app to solve it earlyer, it is called raycast and is a search/launch bar in steroids, as it also serves as a shortcut manager and allows you to conduct many of the usual tasks in your computer, change audio io devices, and even throw conffeti in your screen.

- linux: pop shell launch bar
- macos: reaycast

### keyboard setup

now regarding the rsi it doesn't matter if you have a real good interface if the physiscal hardware you're using isn't comfortable and ergonomic. usually my hands would cramp after half an hour. after a visit to the doc and a very expensive recommendation i got a splic concave columnar keyboard from kinesis, the kinesis 360 pro. it took about a month to get completely used to it, and to it's novel distribution but it eliminated most of the pain and inflamation. (experience may vary)

with the time i started to customize the layout and to optimize to my use case(this will be explained in another blog post in more detail). in the end i decided to use less keys than it actually has (mimicing the zsa voyager) making sure no finger has to travel too much in order to make the expected input. i heavily use homerow mods, and mod morph to achieve a compact fully functional keyboard experience. the meh and hyper key will become my best friends(system wide shourtcuts that i can set up in multiple oses without clashing perfect).

#### system wide shortcuts

|action|shortcut|
|---|---|
|||
|launch file explorer|hyp-f|
|launch email client|hyp-e|
|launch terminal|hyp-t|
|launch browser|hyp-b|
|launch code editor|hyp-c|
|||
|launch bar|hyp-spc|
|window switcher|meh-spc|
|close focused window|hyp-q|
|||
|move focus in direction|hyp-direction|
|move focus to next workspace|hyp-u|
|move focus to prev workspace|hyp-i|
|move focus to specific workspace|hyp-number|
|||
|move focused window in direction|meh-direction|
|move focused window to prev/next monitor|meh-y/p|
|move focused window to prev/next workspace|meh-i/u|
|move focused window to specific workspace|meh-number|
|move focused workspace to next monitor|meh-tab|
|||
|change orientation of focused parent|hyp-o|
|toggle stacking/tiling of focused parent|hyp-s|
|toggle float/tile for focused window|hyp-g
|||
|record screen|hyp-r|
|print screen|hyp-p|
|||
|show applications|hyp-a|
|show workspaces|hyp-d|
|||
|enter adjustment mode(*)|hyp-enter|
|accept*|enter|
|cancel*|esc|
|change orientation*|o|
|toggle stack mode*|s|
|flatten/reset workspace|r|
|move focused window in direction*|direction|
|resize window*|shift-direction|
|join to node/swap window*|ctrl-direction|

* only achievable within adjustment mode.



## benefits of a consistent interface

the advantages of this setup have been substantial:

1. **seamless transitions**: switching between linux and macos now feels almost imperceptible from an interaction/muscle memory perspective.

2. **reduced cognitive load**: the consistent interface minimizes the mental effort required to switch contexts between different machines or operating systems.

3. **enhanced ergonomics**: as a beneficial side effect, the reduction in unnecessary movement and the ergonomic setup have significantly reduced rsi symptoms.

4. **flexibility**: this setup allows me to quickly adapt to new work environments, even when i don't have control over the os choice on my work machine.

the effort invested in finding and configuring aerospace for macos paid off significantly in achieving a truly consistent experience across platforms.


## conclusion

creating a consistent cross-platform computer interface has been a game-changer. while initially motivated by rsi concerns, the benefits in terms of productivity, cognitive ease, and flexibility have exceeded my expectations.

for people that is frequently switching between operating systems, i highly recommend exploring a similar setup. the key is to find tools and configurations that can be mirrored across your systems as closely as possible. in my case, the combination of pop shell on linux and aerospace on macos enabled me in achieving this consistency. with some initial investment in setup, testing, and learning, you can create a seamless computing experience that transcends operating system boundaries.
