---
layout: post
title:  "Netrunner is Turing complete"
date:   2023-08-26 12:00:00
categories: news
tags: [news]
image:
  path: /images/turing-complete/turing.jpg
  feature: /turing-complete/turing.jpg
  credit: Adam S. Doyle
  creditlink: https://adamsdoyle.com/illustration
---

*But can it run Doom?*

Stimhack forum user callforjudgement recently made [a post](https://forum.stimhack.com/t/netrunner-is-turing-complete/11190) presenting [their proof](http://ais523.me.uk/articles/netrunner-is-turing-complete.html) that Netrunner is Turing complete. It's a pretty dense read, but very interesting.

It's long been speculated that this could be possible. A few years back, there was a bit of commotion online about a paper showing that [Magic: The Gathering was Turing complete](https://arxiv.org/abs/1904.09828). It's also been known for some time that [Netrunner contains NP-hard problems](https://arxiv.org/abs/1710.05121).

The proof is using a collection of different techniques to lock down both the runner and corp players so their only options are to take certain desired actions. This results in a stable loop which can be used to model a Turing machine.

One important limitation of the proof is that the players are not completely without agency. This would be almost impossible to achieve in the current card pool. Instead, a number of game ending conditions are set up so as to make any actions but the desired ones end the game in a loss for the player in question, meaning an "optimal player" would never take them. This is a bit "softer" than the full lockdown achieved in the MtG proof, and you have to accept this premise for the construction to work.

[![Whitespace](https://card-images.netrunnerdb.com/v1/large/30074.jpg)](https://netrunnerdb.com/en/card/30074)
[![Always Be Running](https://card-images.netrunnerdb.com/v1/large/09041.jpg)](https://netrunnerdb.com/en/card/09041)

Some of the key pieces involve the ice [Whitespace](https://netrunnerdb.com/en/card/30074), which is used to manipulate the runner's credit total and effect different outcomes depending on the runner's credits, as well as [Hourglass](https://netrunnerdb.com/en/card/02071), which drains their clicks to keep them constrained. [Always Be Running](https://netrunnerdb.com/en/card/09041) ensures the runner must always start their turn by making a run, and all servers but one are protected by ice that will kill the runner to ensure they will run the one server which will maintain the loop.

Another fascinating aspect is the "sword of damocles" remote which is used to create a trap for the corp to make it unfeasible for them to use the purge action, which could otherwise break the loop. If the corp purges, access to this remote is unlocked for the runner, resulting in their victory and a loss for the corp.

I'm not going to go into more detail here, but instead urge everyone who's interested to [read the proof](http://ais523.me.uk/articles/netrunner-is-turing-complete.html) themselves. It's an impressive feat.

### References

**Cards mentioned:**  
[Whitespace](https://netrunnerdb.com/en/card/30074)  
[Hourglass](https://netrunnerdb.com/en/card/02071)  
[Always Be Running](https://netrunnerdb.com/en/card/09041)  

**Other:**  
[Netrunner is Turing complete](https://forum.stimhack.com/t/netrunner-is-turing-complete/11190), Stimhack forum post  
[The proof](http://ais523.me.uk/articles/netrunner-is-turing-complete.html)  
[Magic: The Gathering is Turing Complete](https://arxiv.org/abs/1904.09828), research paper  
[Netrunner Mate-in-1 or -2 is Weakly NP-Hard](https://arxiv.org/abs/1710.05121), research paper  
