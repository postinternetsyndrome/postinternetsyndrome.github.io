---
layout: post
title:  "A loaded question"
date:   2025-02-08 10:00:00
categories: news
tags: [cr, cr-1.4, cr-24.03]
image:
  feature: a-loaded-question/malandragem.jpg
  credit: Null Signal Games/Adam S. Doyle
  creditlink: https://adamsdoyle.com/nsg-netrunner-cards
---

*With the possible exception of ~~the equator~~ **facedown runner cards**, everything begins somewhere.*  
-- *C. S. Lewis*

There's been some talk recently about a fun combo, and I want to talk about it too!

![Rules criminal](\images\a-loaded-question\rules-criminal.png)

Sorry officer, it's my God-given right!

This is not exactly breaking news, but it's a niche interaction that has not received a lot of attention before. We're talking today about [Assimilator](https://netrunnerdb.com/en/card/21008).

[![Assimilator](https://card-images.netrunnerdb.com/v2/large/21008.jpg)](https://netrunnerdb.com/en/card/21008)
[![Apex](https://card-images.netrunnerdb.com/v2/large/09029.jpg)](https://netrunnerdb.com/en/card/09029)

# Booting up
Assimilator is a jank classic, fundamentally built to let [Apex](https://netrunnerdb.com/en/card/09029) ignore its restriction on installing non-virtual resources. But, interestingly, its novel method of putting cards into play (flipping facedown cards faceup) skips the formal install step and makes a number of cards behave outside of their normal parameters. Most notably, it was observed around the card's release that [Cyber-Cypher](https://netrunnerdb.com/en/card/03044) evades the single server restriction when being flipped instead of installed, since the restriction is encoded in the "when installed" ability. This leaves you with one of the strongest generic decoders in the game, numbers-wise, for the low low price of 5c to install Assimilator and 2 clicks to flip. It's efficient as all hell, for certain very large values of "efficient".[^1]

[![Cyber-Cypher](https://card-images.netrunnerdb.com/v2/large/03044.jpg)](https://netrunnerdb.com/en/card/03044)
[![Boomerang](https://card-images.netrunnerdb.com/v2/large/26075.jpg)](https://netrunnerdb.com/en/card/26075)

Later, in the NSG era, people pointed out that [Boomerang](https://netrunnerdb.com/en/card/26075) worked similarly, and that flipping it with Assimilator allowed it to break any ice. Boomerang continued to be a recurring part of the Apex subculture over the years, but the interaction remained a novelty, utilized mainly for quizzes and internet points.

But now... it's still a novelty. But a new aspect of Assimilator has been revealed.

> **[CR 24.03](https://rules.nullsignal.games/?r=sec_load_and_empty)**  
> **10.9.1** To load a card with counters is to place those counters on that card. A card is empty when it is no longer hosting any counters of a type that were previously loaded onto it.  
> **10.9.2** An ability on a card that refers to that card becoming empty is always linked to a preceding ability on that same card that loaded it with counters.

Flipping cards also bypasses load/empty triggers! This means that credits and power counters are never placed on cards which would normally have them. Most of the time, this matters very little. Yes, you can flip [Daily Casts](https://netrunnerdb.com/en/card/26094), but then you just have an empty Daily Casts. But it turns out there are exactly two cards which transcend this boring default: [Earthrise Hotel](https://netrunnerdb.com/en/card/31039) and [Juli Moreira Lee](https://netrunnerdb.com/en/card/34084).

[![Earthrise Hotel](https://card-images.netrunnerdb.com/v2/large/31039.jpg)](https://netrunnerdb.com/en/card/31039)
[![Juli Moreira Lee](https://card-images.netrunnerdb.com/v2/large/34084.jpg)](https://netrunnerdb.com/en/card/34084)

Unlike every other card which loads power counters, these two are not worded in a way which makes removing the counter a cost to activate their ability[^2]. They just instruct you to remove a counter and do an effect, independently of each other. This makes them uniquely positioned to benefit from being flipped into play by Assimilator. If set up this way, they stay in play indefinitely, providing their benefit every single turn. Juli is particularly compelling here since she helps mitigate the *savage* tempo loss from using Assimilator in the first place.

Is this outrageously overpowered? Obviously not. But it's very fun! I want to shout out [Toron](https://netrunnerdb.com/en/decklist/99b0341e-a725-462f-8fc6-75a39992c4ef/a-re-boot-up-your-ass-imilator-2-1-ctk), who brought a deck using this combo to a [CT last week](https://alwaysberunning.net/tournaments/4681/dalfort-grid-february-ctk) and took it to 5th place, which is what drew my attention to this whole thing.

Since Apex is long gone, the current generation of Assimilator decks use [Reboot](https://netrunnerdb.com/en/card/22023) to install cards facedown from the heap. This necessarily means that the setup time is significant. You can't just draw your combo and play it; you must proactively seed the heap with the specific cards you want to flip later. There are some other fun includes in this deck, like [Basilar Synthgland](https://netrunnerdb.com/en/card/33086), which will certainly[^3] come in handy for clawing back some of the tempo you spent getting this Rube Goldberg machine online.

[![Reboot](https://card-images.netrunnerdb.com/v2/large/22023.jpg)](https://netrunnerdb.com/en/card/22023)
[![Basilar Synthgland](https://card-images.netrunnerdb.com/v2/large/33086.jpg)](https://netrunnerdb.com/en/card/33086)

It's worth noting that [decks with Assimilator and Earthrise Hotel](https://netrunnerdb.com/en/decklists/find?faction=&cards%5B%5D=21008&cards%5B%5D=31039&sort=date&rotation_id=&author=&title=&is_legal=&mwl_code=&cycle_28=liberation&packs%5B%5D=rwr&packs%5B%5D=tai&cycle_26=borealis&packs%5B%5D=ph&packs%5B%5D=ms&packs%5B%5D=msbp&packs%5B%5D=su21&packs%5B%5D=sg&packs%5B%5D=sm&packs%5B%5D=mor&cycle_21=ashes&packs%5B%5D=ur&packs%5B%5D=urbp&packs%5B%5D=df&packs%5B%5D=sc19&packs%5B%5D=napd&packs%5B%5D=mo&packs%5B%5D=rar&cycle_16=kitara&packs%5B%5D=ka&packs%5B%5D=win&packs%5B%5D=tdatd&packs%5B%5D=cotc&packs%5B%5D=dtwn&packs%5B%5D=ss&packs%5B%5D=core2&cycle_14=terminal-directive&packs%5B%5D=tdc&packs%5B%5D=td&cycle_13=red-sand&packs%5B%5D=cd&packs%5B%5D=fm&packs%5B%5D=baw&packs%5B%5D=eas&packs%5B%5D=so&packs%5B%5D=dc&cycle_12=flashpoint&packs%5B%5D=qu&packs%5B%5D=ml&packs%5B%5D=in&packs%5B%5D=es&packs%5B%5D=bm&packs%5B%5D=23s&cycle_11=mumbad&packs%5B%5D=ftm&packs%5B%5D=tlm&packs%5B%5D=si&packs%5B%5D=dag&packs%5B%5D=bf&packs%5B%5D=kg&packs%5B%5D=dad&cycle_9=sansan&packs%5B%5D=uot&packs%5B%5D=oh&packs%5B%5D=uw&packs%5B%5D=cc&packs%5B%5D=bb&packs%5B%5D=val&packs%5B%5D=oac&cycle_7=lunar&packs%5B%5D=ts&packs%5B%5D=atr&packs%5B%5D=uao&packs%5B%5D=fc&packs%5B%5D=tsb&packs%5B%5D=up&packs%5B%5D=hap&cycle_4=spin&packs%5B%5D=dt&packs%5B%5D=fal&packs%5B%5D=tc&packs%5B%5D=mt&packs%5B%5D=st&packs%5B%5D=om&packs%5B%5D=cac&cycle_2=genesis&packs%5B%5D=fp&packs%5B%5D=hs&packs%5B%5D=asis&packs%5B%5D=ce&packs%5B%5D=ta&packs%5B%5D=wla&packs%5B%5D=core) exist on NetrunnerDB as far back as 2020, most of them in Apex. This implies that the interaction has been known (since Apex is forbidden from installing Earthrise Hotel normally), but maybe not widely. The load/empty rule was introduced with [CR 1.4](https://nullsignal.games/wp-content/uploads/2021/08/NISEI-Comprehensive-Rules-v1.4-2019-12-20.pdf) in December 2019, and Earthrise Hotel was reprinted with the new wording in System Update 2021. Arguably, the older wording on Earthrise Hotel should have worked the same way though:

> Place 3 power counters on Earthrise Hotel when it is installed. When there are no power counters left on Earthrise Hotel, trash it.

This is all one ability, so the link between the install trigger and trashing the card is present in this version too. We just never realized it until much later.

Now, would the game's designer (Michael Boggs at the time) have sanctioned this interpretation if it had been put to the test? We don't know of course. FFG were not always consistent in their rulings and it's possible they would have shot this one down. But Boggs was the one who codified the Cyber-Cypher interaction in the [UFAQ](https://ancur.fandom.com/wiki/Sovereign_Sight_UFAQ#Assimilator) released alongside Assimilator, so it's not out of the realm of possibility.

# And, for my next trick...
There is one other card which cares - slightly - about Assimilator bypassing load/empty. [Malandragem](https://netrunnerdb.com/en/card/34081) has the annoying property of trashing itself once you've used all the power counters, so you have to save a counter if you want to use the threat ability, which then goes to waste when the card removes itself from the game. With Assimilator, you could imagine getting a full two uses out of the card, and then later rebooting it back for assimilation, allowing you to use it a final time, with the threat text. The value!

Also, there's the extremely niche use of [Bank Job](https://netrunnerdb.com/en/card/25038) as a way to opt out of accessing cards after making a successful run on a remote. For obvious reasons, this is not a widely sought after effect! (Additionally, you can already do this with a Bank Job installed normally, since you can always choose to take 0 credits from it. So if you leave it around with 1 credit you get this utility much cheaper and simpler than doing the whole Assimilator thing...)

[![Malandragem](https://card-images.netrunnerdb.com/v2/large/34081.jpg)](https://netrunnerdb.com/en/card/34081)
[![Bank Job](https://card-images.netrunnerdb.com/v2/large/25038.jpg)](https://netrunnerdb.com/en/card/25038)

Have you found luck with an Assimilator deck recently? I'm curious about different ways of making this one work. I don't expect we'll see it ravage the tournament circuit any time soon, even if drawing two free cards every turn is a strong effect, that historically some decks spent 6 credits and 6 deck slots to [set](https://netrunnerdb.com/en/card/01016) [up](https://netrunnerdb.com/en/card/08003). That's not too far off from the Reboot + Assimilator combination![^4]

[![Wyldside](https://card-images.netrunnerdb.com/v2/large/01016.jpg)](https://netrunnerdb.com/en/card/01016)
[![Adjusted Chronotype](https://card-images.netrunnerdb.com/v2/large/08003.jpg)](https://netrunnerdb.com/en/card/08003)

The main problem[^5] seems to be that the influence cost of Assimilator and Reboot are both 5, so if you want to import any other cards at all you're relegated to running only one of each. This to me implies crim is the natural home of these decks, since they already have Juli and some of the other likely targets in faction. (Expensive cards like [Amina](https://netrunnerdb.com/en/card/21104), cybernetics like [WAKE Implant](https://netrunnerdb.com/en/card/33078) and [Zenit Chip](https://netrunnerdb.com/en/card/33079), Boomerang.) They also have potential enablers like [Meeting of Minds](https://netrunnerdb.com/en/card/34076) and [Career Fair](https://netrunnerdb.com/en/card/31015) which might make pulling the whole thing off a bit easier. Toron's deck is built in [Ken](https://netrunnerdb.com/en/card/31013), which also makes sense in this context since he has 2 extra influence.

Anarch, on the other hand, has [Gachapon](https://netrunnerdb.com/en/card/26069), which could be useful for both finding your Assimilator and seeding the heap with Reboot targets. And Shaper has great draw. Who will get there first?

With the release of [Elevation](https://nullsignal.games/blog/welcome-to-elevation/) in April this year, the essential cards in this combo will rotate, so the time to jank is now!

### References
This article uses the [NSG Comprehensive Rules Document version 24.03](https://access.nullsignal.games/CompRules/Null_Signal_Games_Netrunner_Comprehensive_Rules_v24.03.pdf), which was released on 30 march 2024.

For convenience of linking, this article also uses the [NSG online rules](https://rules.nullsignal.games/), which is an html rendering of the CR where you can link directly to individual rules. This is a volatile document and links to whichever version of the CR is the current one. Hopefully NSG will provide permalinks to older rules documents in this format in the future. If you find that links in this article are broken, let me know!

**Rules mentioned:**  
*Chapter 10: Additional Rules*  
[10.9.1](https://rules.nullsignal.games/?r=rule_load_and_empty) (p.88)  
[10.9.2](https://rules.nullsignal.games/?r=rule_empty_requires_loading) (p.88)

**Cards mentioned:**  
[Assimilator](https://netrunnerdb.com/en/card/21008)  
[Apex](https://netrunnerdb.com/en/card/09029)  
[Cyber-Cypher](https://netrunnerdb.com/en/card/03044)  
[Boomerang](https://netrunnerdb.com/en/card/26075)  
[Daily Casts](https://netrunnerdb.com/en/card/26094)  
[Earthrise Hotel](https://netrunnerdb.com/en/card/06120)  
[Juli Moreira Lee](https://netrunnerdb.com/en/card/34084)  
[Reboot](https://netrunnerdb.com/en/card/22023)  
[Basilar Synthgland 2KVJ](https://netrunnerdb.com/en/card/33086)  
[Malandragem](https://netrunnerdb.com/en/card/34081)  
[Bank Job](https://netrunnerdb.com/en/card/25038)  
[Wyldside](https://netrunnerdb.com/en/card/01016)  
[Adjusted Chronotype](https://netrunnerdb.com/en/card/08003)  
[Amina](https://netrunnerdb.com/en/card/21104)  
[WAKE Implant v2A-JRJ](https://netrunnerdb.com/en/card/33078)  
[Zenit Chip JZ-2MJ](https://netrunnerdb.com/en/card/33079)  
[Meeting of Minds](https://netrunnerdb.com/en/card/34076)  
[Career Fair](https://netrunnerdb.com/en/card/31015)  
[Ken "Express" Tenma](https://netrunnerdb.com/en/card/31013)  
[Gachapon](https://netrunnerdb.com/en/card/26069)

**Other:**  
[A (re)Boot up your Ass(imilator) 2-1 @ CTK](https://netrunnerdb.com/en/decklist/99b0341e-a725-462f-8fc6-75a39992c4ef/a-re-boot-up-your-ass-imilator-2-1-ctk), NetrunnerDB decklist  
[DalFort Grid February CTK](https://alwaysberunning.net/tournaments/4681/dalfort-grid-february-ctk), Always be Running tournament page  
[Decks with Assimilator and Earthrise Hotel](https://netrunnerdb.com/en/decklists/find?faction=&cards%5B%5D=21008&cards%5B%5D=31039&sort=date&rotation_id=&author=&title=&is_legal=&mwl_code=&cycle_28=liberation&packs%5B%5D=rwr&packs%5B%5D=tai&cycle_26=borealis&packs%5B%5D=ph&packs%5B%5D=ms&packs%5B%5D=msbp&packs%5B%5D=su21&packs%5B%5D=sg&packs%5B%5D=sm&packs%5B%5D=mor&cycle_21=ashes&packs%5B%5D=ur&packs%5B%5D=urbp&packs%5B%5D=df&packs%5B%5D=sc19&packs%5B%5D=napd&packs%5B%5D=mo&packs%5B%5D=rar&cycle_16=kitara&packs%5B%5D=ka&packs%5B%5D=win&packs%5B%5D=tdatd&packs%5B%5D=cotc&packs%5B%5D=dtwn&packs%5B%5D=ss&packs%5B%5D=core2&cycle_14=terminal-directive&packs%5B%5D=tdc&packs%5B%5D=td&cycle_13=red-sand&packs%5B%5D=cd&packs%5B%5D=fm&packs%5B%5D=baw&packs%5B%5D=eas&packs%5B%5D=so&packs%5B%5D=dc&cycle_12=flashpoint&packs%5B%5D=qu&packs%5B%5D=ml&packs%5B%5D=in&packs%5B%5D=es&packs%5B%5D=bm&packs%5B%5D=23s&cycle_11=mumbad&packs%5B%5D=ftm&packs%5B%5D=tlm&packs%5B%5D=si&packs%5B%5D=dag&packs%5B%5D=bf&packs%5B%5D=kg&packs%5B%5D=dad&cycle_9=sansan&packs%5B%5D=uot&packs%5B%5D=oh&packs%5B%5D=uw&packs%5B%5D=cc&packs%5B%5D=bb&packs%5B%5D=val&packs%5B%5D=oac&cycle_7=lunar&packs%5B%5D=ts&packs%5B%5D=atr&packs%5B%5D=uao&packs%5B%5D=fc&packs%5B%5D=tsb&packs%5B%5D=up&packs%5B%5D=hap&cycle_4=spin&packs%5B%5D=dt&packs%5B%5D=fal&packs%5B%5D=tc&packs%5B%5D=mt&packs%5B%5D=st&packs%5B%5D=om&packs%5B%5D=cac&cycle_2=genesis&packs%5B%5D=fp&packs%5B%5D=hs&packs%5B%5D=asis&packs%5B%5D=ce&packs%5B%5D=ta&packs%5B%5D=wla&packs%5B%5D=core), NetrunnerDB deck search  
[NSG Comprehensive Rules Document version 1.4](https://nullsignal.games/wp-content/uploads/2021/08/NISEI-Comprehensive-Rules-v1.4-2019-12-20.pdf)  
[Sovereign Sight unofficial FAQ](https://ancur.fandom.com/wiki/Sovereign_Sight_UFAQ#Assimilator)  
[Welcome to Elevation](https://nullsignal.games/blog/welcome-to-elevation/), NSG blog post
## Acknowledgements
*Factchecking*  
Cephalopod Wizard  

### Footnotes
[^1]: [BT's Guide to Icebreaking](https://netrunnerdb.com/en/card/04026)
[^2]: There are of course many other cards which use power counters in different ways. Some of them have effects on install that you can dodge with Assimilator, like cybernetics, but doing so doesn't fundamentally change their function, unlike the load/empty situation.
[^3]: Terms and conditions may apply.
[^4]: It's about two clicks off.
[^5]: (apart from assembling the combo before the heat death of the universe)