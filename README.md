# SteamBoat
Like TrashBoat, but for Steam.
This is currently just a placeholder repository for what I'm thinking about cooking up, if I'm ever not lazy after work.

## Overview
The idea here is to create a newer version of a Steam card idling tool in order to blend the best features of ASF and IdleMaster Extended.
Hopefully, as I learn the Steam API, I can create a program with a slick GUI that's easy to use and powerful at the same time.

## Features
SteamBoat aims to address the following:

### ArchiSteamFarm (ASF): 
ASF is versatile and extremely powerful with a high level of customization for power users.  However, I've found it a bit overwhelming to set up and I've never been able to get the idling algorithm to be nearly as effective as the one that IdleMaster Extended uses these days.  If I had to list the positives and negatives for ASF, it would look something like this.

Pros:
* Once you get logged in, you almost never have to repeat the process.
* Allows multiple accounts, if you need that sort of thing.
* Has a ton of bells and whistles for managing accounts as if they're bots.

Cons:
* Complex and can overwhelm the user.
* Acts as it's own steam client, so if you want to idle cards while playing something else, that doesn't really work from what I can find.
* Idling algorithm produces results slower than Idlemaster Extended.
* Additionally, since the results are slower, this leads to additional bloating of a game's playtime in order to get all drops.

### IdleMaster Extended
IdleMaster Extended is definitely the more basic and user friendly idling option.  But the last time I used it, I was repeatedly logged out and every time I would open it to have it idle my games, I would be forced to go look up the cookie from my browser and get the sessionId and steamLoginSecure values all over again.  It got frustrating enough that I returned to using ASF, even though IdleMaster Extended does a much quicker job on idling and producing results.  The positives/negatives for it look something like this.

Pros:
* Can idle while playing a game on the same PC since it uses the login info from the cookie from your browser.
* Quicker and more efficient to knock out the cards if you've built up a giant backlog.
* Additionally, if you care about playtime on your games, this will help keep the bloat from idling minimal.

Cons:
* You have to log in constantly.  Almost every time you reboot your pc and reopen it, in my recent experience.
* Logging in is not easy or convenient as you have to go hunt down a cookie after logging in via browser.

## Goals
My goal is to create something that takes what I consider to be the positives of the two existing solutions and put them together in a way that erases the weaknesses outlined above.  Ideally you will be given an option to browse to the cookie associated with the login you wish to use and then the program can read the values every time if the session isn't able to persist in some way, however ASF is managing to do that.  Once your logged in and it's persistent, the goal would be to use the slamma-jamma method of idling to blitz through the backlog of games with card drops remaining.  

A secondary goal might be to see if whatever I write for this program can get ported to linux and maybe get it up and running on steam deck.