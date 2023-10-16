---
layout: post
title:  "Combo spotlight: Dancing Devas"
date:   2023-10-15 12:00:00
categories: news
tags: [news, cr, cr-23.08]
---

*"Being a particularly clever boy, I made the sensible decision to invest the money. I invested it in drink and expensive food and stylish clothes and in buying myself a lot of friends at the local inn."*

> **Update 2023-10-16** 
- The [decklist](https://netrunnerdb.com/en/decklist/49e43583-25b8-439e-98c0-dc97a0f35ca7/-eternal-hacker-hall-of-fame-undefeated-worlds-2023) has now been published on NRDB. Head over there and give it a like!

Today we bring you a quick update on a recent *rules development*!

Right after the release of the Automata Initiative on July 31, NSG put out [an article](https://nullsignal.games/blog/the-automata-initiative-rules-highlights/) with some quick discussion on various upcoming rules changes relevant to the new cards. A week later, on August 7, the full [Comprehensive Rules v23.08](https://access.nullsignal.games/CompRules/Null-Signal-Games-Netrunner-Comprehensive-Rules-v23.08.pdf) was published, which contains all the gory details behind those changes.

Of primary interest to us today - and to most people at the time as well - is an addition to the swapping rules. Rule 8.8.4.b. was extended with text confirming a previously obscure interpretation that swapping a card from a non-installed zone to an installed one actually triggers on install effects. It reads thusly (new additions in bold):

> **[CR 23.08](https://rubenpieters.github.io/netrunner-comprehensive-rules/#rule_swap_become_installed)**  
> If only one of the cards to be swapped is installed, then it becomes uninstalled as it moves to the destination zone. Any cards or counters hosted on it are trashed. The other card becomes installed in the exact position the first card occupied, maintaining any specific location (such as server, ice position, or host). **The normal procedure for installing a card is not followed, so no install cost is paid and like cards cannot be trashed. At the next checkpoint after the swap takes place, trigger conditions related to uninstalling or installing the two cards are met, respectively.**

Or, if you prefer the more conversational explanation from the rules highlight article:

> When you swap a card that is installed with a card that is not installed, the new card will become installed and trigger any abilities that may be relevant at that time, such as that of the new Jinteki identity, [A Teia](https://netrunnerdb.com/en/card/34039). When you perform a swap like this, you do not pay install costs, and you may not trash any cards in the root of or protecting the server as part of the install. Swapping two cards that are already installed does not cause either of them to become newly installed, and so does not trigger abilities in this way.

# The secret history
The interesting thing from a rules-historical perspective is that this was, from a certain point of view, not a new rule. Classically, it has been understood that swapping does *not* trigger on install effects, based on a [2016 Damon Stone ruling](https://ancur.fandom.com/wiki/Democracy_and_Dogma_UFAQ#Sadyojata) for the Deva[^1] cards (a trio of cards with a shared ability to swap a currently installed one with another from your hand):

> **ANCUR:** Is swapping Sadyojata with another Deva considered an installation?  
> **Damon Stone:** No. Swapping just exchanges the places of the two cards. 

This looks pretty definitive. However, when the rules team reviewed FFG rulings on NRDB almost two years ago, they decided that the even older (but to many probably lesser known) FAQ entries for [Midori](https://netrunnerdb.com/en/card/02113) took precedence:

> Ice that is swapped is installed, but the install cost of the ice being swapped does not have to be paid.

> Ice installed with Midori can be rezzed with the [Amazon Industrial Zone](https://netrunnerdb.com/en/card/02038).

The first one of these uses vague language reminiscent to the "becomes installed" wording that made the previous CR a bit ambiguous as to the exact intent, but the second one clearly establishes the precedent that effects that trigger off of the installation of a card also work with swapping.

This is in many ways reasonable, because the Midori rulings were in the official [FAQ 1.3](http://web.archive.org/web/20131022032232/http://www.fantasyflightgames.com/ffg_content/android-netrunner/support/FAQ/Android-Netrunner%20FAQ.pdf), all the way back in 2013. They were always there, never officially reversed, just ignored. However, many players were no doubt surprised when this interpretation was "suddenly" codified in the CR this summer.

[![Sadyojata](https://card-images.netrunnerdb.com/v1/large/10044.jpg)](https://netrunnerdb.com/en/card/10044)
[![Midori](https://card-images.netrunnerdb.com/v1/large/02113.jpg)](https://netrunnerdb.com/en/card/02113)

The inconsistent Deva rulings were removed from NRDB in 2022, but this wasn't accompanied by any larger announcement, and was certainly not noticed by this author at least. Many of us definitely continued to reference those Deva rulings when the question occasionally came up, unaware that they had been off the books for almost two years.

At the time of the new CR release, the cards most in the spotlight with regards to this ruling were [Tatu-Bola]() - which probably deserves its own article at some point - and the aforementioned A Teia, but in this article we're going to look a bit closer at those Devas.

# Deva Ex Machina
[Worlds 2023](https://nullsignal.games/blog/worlds-schedule-announcement/) is currently in progress, and one of the traditional side events is the team tournament, known as [Crown of Servers](https://alwaysberunning.net/tournaments/3810/2023-crown-of-servers-team-tournament#). This year, they put an additional twist on it: Each player on the team plays a different format. Standard, Startup and Eternal are all represented on each team. This has meant that some classic combo decks have been reliving their glory days - CI, Dyper, etc. But we've also seen some new tech, powered by the new swap ruling.

The idea for this combo isn't brand new - it was discussed when the swap ruling hit the news - but its appearance this weekend feels like a good excuse to shine a light on it.

Here's how it works:

You play [In the Groove](https://netrunnerdb.com/en/card/26020), [Scheherazade](https://netrunnerdb.com/en/card/04022) and [Technical Writer](https://netrunnerdb.com/en/card/09055). Next, install one of the Devas (it doesn't matter which particular one) on Scheherazade, gaining 2 credits - one from In the Groove and one from Scheherazade. Technical Writer also gets a credit on it. Now you're all set. Use the swap ability on the Deva to bring in another from your hand. This costs 2c, but you also gain 2c. And, crucially, Technical Writer gets a credit. You may now proceed to repeat this operation a gratuitous number of times (say, one thousand and one). When you're done, pop Technical Writer and quit your [Day Job](https://netrunnerdb.com/en/card/07036).

[![In the Groove](https://card-images.netrunnerdb.com/v1/large/26020.jpg)](https://netrunnerdb.com/en/card/26020)
[![Scheherazade](https://card-images.netrunnerdb.com/v1/large/04022.jpg)](https://netrunnerdb.com/en/card/04022)

[![Technical Writer](https://card-images.netrunnerdb.com/v1/large/09055.jpg)](https://netrunnerdb.com/en/card/09055)
[![Aghora](https://card-images.netrunnerdb.com/v1/large/10097.jpg)](https://netrunnerdb.com/en/card/10097)

At this point, you may proceed to win the game at your leisure. You can continue drawing cards with In the Groove by Deva swapping some more after you cash out the Technical Writer, so you get immediate access to your win condition. The [deck](https://netrunnerdb.com/en/decklist/49e43583-25b8-439e-98c0-dc97a0f35ca7/-eternal-hacker-hall-of-fame-undefeated-worlds-2023) played at Crown of Servers runs [Vamp](https://netrunnerdb.com/en/card/02021) for this purpose. I'm sure there are other valid options, but Vamp certainly seems like one of the simplest ways to leverage a large credit count into a win.

Amusingly, the breaker of choice for this deck is the oft-maligned [Wyrm](https://netrunnerdb.com/en/card/01013), because it's an AI breaker without any restrictions other than being extremely expensive to use. The ID is [Kabonesa Wu](https://netrunnerdb.com/en/card/21025) of course, so you can assemble the combo (which isn't even that complex to begin with) lightning fast.

[![Vamp](https://card-images.netrunnerdb.com/v1/large/02021.jpg)](https://netrunnerdb.com/en/card/02021)
[![Wyrm](https://card-images.netrunnerdb.com/v1/large/01013.jpg)](https://netrunnerdb.com/en/card/01013)

Under the Damon Stone ruling this combo wouldn't be possible, but now with *Lex Midori* all three of these credit-generating cards get triggered by the Deva swap, giving us a repeatable +1 credit gain at paid ability speed. No interaction with the corp is required.

A video from the event is available on the NSG twitch channel [here](https://www.twitch.tv/videos/1949780388). Unfortunately, this particular combo deck never made it on stream, but there are many other fun games to watch.

Fun trivia: This combo is not *technically* an "infinite loop" in the terminology of the CR[^2] (and we're all about the *technically* on this blog, obviously). The rules contain [two separate clauses](https://rubenpieters.github.io/netrunner-comprehensive-rules/#sec_infinite_loops) about infinite loops. They refer to "mandatory infinite loops" and "optional infinite loops during a run", respectively. In the first case, the player resolving the loop gets to pick a number and then the loop resolves that many times before exiting. (A rare instance of the rules just creating an ad hoc exception to the normal control flow of the game's timing structures out of thin air.) In the second case, the players are required to make choices that will end the loop.

What we have here, though, is an optional loop *outside* any runs. This means there are no official provisions for short-circuiting the loop, and no formal requirement to cause it to end. According to the rules as written, you would be expected to manually perform all the iterations the desired number of times. In practice no one will do this, of course. They'll just say "I have infinite credits now" and move on. And if you decided that you wanted to continue executing the loop ad nauseum, you'd probably be penalized for slow play.

# Counterplay
It was observed on Stimslack that there are some hilarious potential answers to this combo. [Targeted Marketing](https://netrunnerdb.com/en/card/06026) gains 10c each time a given program is installed. If the corp calls their shot correctly, they will gain ten times the number of credits the runner makes, allowing them to shut down the silliness with cards like [Corporate Troubleshooter](https://netrunnerdb.com/en/card/01065) and [Ash 2X3ZB9CY](https://netrunnerdb.com/en/card/02013). There are three different Devas though, so if the runner has access to all three, they can just pick the two not named for Targeted Marketing and stay safe. But if they haven't drawn the full set yet, they might choose to fire the combo in spite of making corp rich as well.

[![Targeted Marketing](https://card-images.netrunnerdb.com/v1/large/06026.jpg)](https://netrunnerdb.com/en/card/06026)
[![TechnoCo](https://card-images.netrunnerdb.com/v1/large/21060.jpg)](https://netrunnerdb.com/en/card/21060)

[TechnoCo](https://netrunnerdb.com/en/card/21060) can achieve a similar result. The Deva swap ability does not care about the increased install costs, so you can't really disrupt the combo itself this way, but you can match their credit gain exactly and potentially stave of the Vamp attack.

### References
This article uses the [NSG Comprehensive Rules Document version 23.08](https://access.nullsignal.games/CompRules/Null-Signal-Games-Netrunner-Comprehensive-Rules-v23.08.pdf), which was released on 9 December 2022.

For convenience of linking, this article also uses NSG rules team member Ruben Pieter's [personal hosted version of the CR](https://rubenpieters.github.io/netrunner-comprehensive-rules/), which is an html rendering of the document where you can link directly to individual rules. This is not an official NSG resource and it may be moved or removed in the future. To learn more about this project, visit the [github repo](https://github.com/rubenpieters/netrunner-comprehensive-rules).

**Rules mentioned:**  
*Chapter 8: Card Manipulation*  
[8.8.4.b.](https://rubenpieters.github.io/netrunner-comprehensive-rules/#rule_swap_become_installed) (p.57)

*Chapter 10: Additional Rules*  
[10.1.6](https://rubenpieters.github.io/netrunner-comprehensive-rules/#sec_infinite_loops) (p.81)  

**Cards mentioned:**  
[A Teia](https://netrunnerdb.com/en/card/34039)  
[Midori](https://netrunnerdb.com/en/card/02113)  
[Amazon Industrial Zone](https://netrunnerdb.com/en/card/02038)  
[In the Groove](https://netrunnerdb.com/en/card/26020)  
[Scheherazade](https://netrunnerdb.com/en/card/04022)  
[Technical Writer](https://netrunnerdb.com/en/card/09055)  
[Day Job](https://netrunnerdb.com/en/card/07036)  
[Vamp](https://netrunnerdb.com/en/card/02021)  
[Wyrm](https://netrunnerdb.com/en/card/01013)  
[Kabonesa Wu](https://netrunnerdb.com/en/card/21025)  
[Targeted Marketing](https://netrunnerdb.com/en/card/06026)  
[Corporate Troubleshooter](https://netrunnerdb.com/en/card/01065)  
[Ash 2X3ZB9CY](https://netrunnerdb.com/en/card/02013)  
[TechnoCo](https://netrunnerdb.com/en/card/21060)  
[Sadyojata](https://netrunnerdb.com/en/card/10044)  
[Aghora](https://netrunnerdb.com/en/card/10097)  
[Vamadeva](https://netrunnerdb.com/en/card/10061)  

**Other:**  
[TAI Rules Highlights](https://nullsignal.games/blog/the-automata-initiative-rules-highlights/), NSG blog post  
[Democracy and Dogma unofficial FAQ](https://ancur.fandom.com/wiki/Democracy_and_Dogma_UFAQ)  
[Android: Netrunner FAQ v1.3](http://web.archive.org/web/20131022032232/http://www.fantasyflightgames.com/ffg_content/android-netrunner/support/FAQ/Android-Netrunner%20FAQ.pdf)  
[Worlds 2023 schedule](https://nullsignal.games/blog/worlds-schedule-announcement/), NSG blog post  
[Crown of Servers](https://alwaysberunning.net/tournaments/3810/2023-crown-of-servers-team-tournament#), ABR page  
[NSG Twitch channel](https://www.twitch.tv/videos/1949780388)  
[Hacker Hall of Fame](https://netrunnerdb.com/en/decklist/49e43583-25b8-439e-98c0-dc97a0f35ca7/-eternal-hacker-hall-of-fame-undefeated-worlds-2023), NRDB decklist

## Acknowledgements
*Proofreading & factchecking*  
essexmcintosh  
Cephalopod Wizard  
OF15-15

Special thanks to Plural, Jamie and Cephalopod Wizard for helping me track down the history of changes to the card rulings on NRDB.

![Screenshot of a Discord conversation](\images\dancing-devas\nrdb-2022.png)

### Footnotes
[^1]: [Sadyojata](https://netrunnerdb.com/en/card/10044), [Aghora](https://netrunnerdb.com/en/card/10097) and [Vamadeva](https://netrunnerdb.com/en/card/10061).

[^2]: Thanks to Mike P on Stimslack for pointing this out.