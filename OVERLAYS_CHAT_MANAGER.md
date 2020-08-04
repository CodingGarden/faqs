# Overlays, Bots and Chat Manager

The overlays, bots and chat manager you see on my screen were all coded live on stream! 

They are not immediately usable by non-technical people, but if you have node.js installed and know how to clone a repo, you might be able to get them running yourself. 

I'm currently in the process of making these things more easily accessible / usable by non-technical people.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Drop Game Overlay](#drop-game-overlay)
- [Stream Alerts / Notifications Overlay](#stream-alerts--notifications-overlay)
- [Twitch Team Shoutout Bot](#twitch-team-shoutout-bot)
- [Chat Controlled 8-bit LED](#chat-controlled-8-bit-led)
- [Chat Manager v1 (Deprecated)](#chat-manager-v1-deprecated)
- [Chat Manager V2 + SproutKit](#chat-manager-v2--sproutkit)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Drop Game Overlay

* Source code:
  * https://github.com/CodingGarden/SeedlingDrop
  * https://github.com/CodingGarden/ChristmasDrop
  * Currently depends on the outdated live-chat-manager backend mentioned below

This game was coded live on stream and was inspired by the [PenguinDrop](https://github.com/instafluff/PenguinDrop) game created by [Instafluff](https://www.twitch.tv/instafluff). I decided to make my own version with a Garden theme!

* Creating initial version: https://www.youtube.com/watch?v=VJFFJAR6AwM
  * (I added the garden theme off stream)
* Creating a christmas themed drop game:
  * Initial: https://www.youtube.com/watch?v=fHWWysLNmeo
  * Updates: https://www.youtube.com/watch?v=a37YpJVQxqM

## Stream Alerts / Notifications Overlay

* Source code: https://github.com/CodingGarden/stream-overlay-alerts

I used to use the default stream labs notification overlay, but there were a few things I didn't like about it:
  * Did not differentiate between gifted subs and regular subs
  * Large amounts of gift subs were announced one after another
  * Bits notifications did not display the users message

The stream alerts overlay I use now was initially created by a moderator of the stream MurdocTurner. He sent me the code, and I began to modify it from there.

* Updating the initial version created by Murdoc: https://www.youtube.com/watch?v=0zmLgSsEO7w
* More updates: https://www.youtube.com/watch?v=dUYfJPhYBVc

## Twitch Team Shoutout Bot

Source code: https://github.com/CodingGarden/twitch-team-shoutout-bot/

A bot that detects when a team member has entered the chat and sends a shout out message. See the README for how to set this up locally.

* Creating the bot: https://www.youtube.com/watch?v=V-Hxb0WArpI

## Chat Controlled 8-bit LED

* Source code:
  * https://github.com/CodingGarden/8-bit-led
  * Currently depends on the outdated live-chat-manager backend mentioned below

This is the 8 LEDs you see on my screen that can be controlled by twitch chat!

* Creating the 8-bit LED: https://www.youtube.com/watch?v=onkzhfXJlp0

## Chat Manager v1 (Deprecated)

* Backend / Frontend Source Code: https://github.com/CodingGarden/live-chat-manager
  * This backend is still in use by the Drop game, but will be entirely replaced / removed soon
* Electron Source Code: https://github.com/CodingGarden/live-chat-window
  * No longer in use

The chat manager was initially created back in the days of YouTube only streaming. It allowed me to keep track of my place in chat and read / acknowledge every single chat message that came through. My channel has grown, and the chat manager has grown with it. I can no longer acknowledge every single message, but my chat manager helps me keep things organized.

* Creating the initial app (YouTube chat only): https://www.youtube.com/watch?v=cDVfs0LnrMg
* Making updates to the app (YouTube chat only): https://www.youtube.com/watch?v=c75rSs5vukk
* Adding Twitch chat: https://www.youtube.com/watch?v=-XHPBXX_iKI
* Converting the chat manager to an Electron app: https://www.youtube.com/watch?v=2PqQvnqsqcg

## Chat Manager V2 + SproutKit

* Back End Source Code: https://github.com/CodingGarden/api
* Front End Source Code: https://github.com/CodingGarden/sproutkit

After I moved to twitch only live streaming, I decided to re-write my chat manager from scratch. Mainly because I no longer needed to wrestle with YouTube APIs, and could focus solely on Twitch APIs. I also wanted to move the codebase towards a state of eventually being usable by other streamers. The code base is not there yet, but I've made progress!

The sproutkit repo contains the source code for my intro / getting started screen overlay, the "pixel house" chat overlay, and the electron chat window you see on my screen.

* The backend was coded off stream.
* Creating SproutKit Components Part 1: https://www.youtube.com/watch?v=flw8yTSPc_4
* Working on SproutKit Components Part 2: https://www.youtube.com/watch?v=E44cqjVMLmY
* Working on SproutKit Components Part 3: https://www.youtube.com/watch?v=_yPzdc59jD0
