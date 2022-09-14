---
layout: post
title:  "Cost and effect"
date:   2022-09-01 12:00:00 +0200
categories: essays
tags: [cr-1.6, ncigs]
image:
  path: /images/overclock.jpg
  feature: overclock.jpg
  credit: Scott Uminga
  creditlink: https://www.scottuminga.com/post/647115414557671424/overclock-niseis-system-gateway-scott-uminga
---

I'm sorry, Dave. I'm afraid you can't do that.

*The year is 2015 and you're in the last round of swiss at a local store championship. It's turn 3 and you have your [Lady](https://netrunnerdb.com/en/card/29006) installed, but it's out of counters. Luckily, you have [Scavenge](https://netrunnerdb.com/en/card/03034) in your grip. You raise your hand and yell "JUDGE!", causing your opponent to levitate briefly. The judge arrives, and you ask: "Can you please confirm that I am allowed play Scavenge here even though my heap is empty?" "Yes indeed, you are", says the judge after glancing at your grip. "Thank you kindly", you say and proceed to reinstall your Lady using Scavenge, as your opponent nods in acknowledgement.*

What is going on?

Few rules concepts in Netrunner are as controversial as "no change in game state" ("NCIGS"). Plenty of new players have butted their heads against this occasionally unintuitive idea, and many have questioned its relevance and utility. I want to talk a bit about how this rule works, what it means, and what would happen if it was removed.

### Contents
- [What is NCIGS?](#what-is-ncigs)  
- [Limitations](#limitations)  
- [Costs](#costs)  
- [Subversion](#subversion)  
- [Exceptions](#exceptions)  
- [Origins](#origins)  
- [Alternate universes](#alternate-universes)  
- [Where we are](#where-we-are)  
- [A challenger appears](#a-new-challenger-appears)  

## What is NCIGS?
Netrunner has a rule that says you can't play a card or use an ability if it won't have an effect. This is colloquially known as the “no change in game state” rule (often ebbreviated "NCIGS"). At first glance, it might seem quite innocuous and intuitive. "You can't do a thing if it doesn't do anything." Makes sense to me! But this simple idea can lead to some surprising results.

Let's take a look at the specifics. The "NCIGS rule" is not actually a single rule - it is mentioned in several places in the NISEI Comprehensive Rules - but the main codification of the concept is in section 1.2, "The Golden Rules":

> **CR 1.2.5** A player can only take an action or use an ability if its effect has the potential to change the game state. This potential is assessed strictly by what the action or ability can be expected to accomplish, without regard to the consequences of paying any costs to initiate that action or ability and without regard to any other abilities that may meet their conditions in the process of initiating or resolving that action or ability.

That's a bit of a mouthful. Let's pick it apart.

> A player can only take an action or use an ability if its effect has the potential to change the game state.

This means that you can't play [Diesel](https://netrunnerdb.com/en/card/31027) if there aren't any cards left in your stack, or use the basic action to pay two credits and remove a tag if you have no tags.

> This potential is assessed strictly by what the action or ability can be expected to accomplish, without regard to the consequences of paying any costs to initiate that action or ability...

The second part of the rule clarifies that even though playing a card might cause obvious changes like your credit total going down when you pay the cost of the card, these changes are irrelevant to the evaluation of NCIGS.

> ...and without regard to any other abilities that may meet their conditions in the process of initiating or resolving that action or ability.

And thirdly, you don't consider changes in game state that might result from other abilities triggering off of things happening during the resolution of the ability you want to use, or after it. (Like [Rejig](https://netrunnerdb.com/en/card/26029) being trashed after use, causing [Aniccam](https://netrunnerdb.com/en/card/26084) to draw a card for you.)

This general formulation of the concept is then further expanded on in a few other sections of the CR. They don't really add that much more detail, and serve mostly to specify exactly which actions and abilities are subject to NCIGS, but I'm including them here for completeness' sake:

> **CR 5.2.4** A player can only take an action if its effect has the potential to change the game state.
See rule 1.2.5.

> **CR 9.1.5b** When determining whether a certain ability has the potential to change the game
state, look only at the expected effects of the ability. Do not consider its costs or
restrictions, and do not consider other abilities that could become pending or
relevant because of triggering or resolving the ability. See rule 1.2.5 of the Golden
Rules.

> **CR 9.1.6d** A player can only use an ability if its effect has the potential to change the game
state. See rule 1.2.5.

> **CR 9.6.7d** A conditional ability with a static condition can only be marked pending if the
instructions in the ability have the potential to change the game state.

In summary, NCIGS is applied when you want to (examples in parentheses):
- **Perform an action** (playing a card, installing a card, drawing a card, making a run)
- **Activate a paid ability** (fetching and installing a program with [SMC](https://netrunnerdb.com/en/card/03046), breaking subroutines with [Corroder](https://netrunnerdb.com/en/card/31006))
- **Resolve an optional ability** (putting a counter on [Conduit](https://netrunnerdb.com/en/card/30024) after a run, trashing an ice with [Hippo](https://netrunnerdb.com/en/card/21103))
- **Activate a conditional ability with a static condition**[^1] (trashing [Dadiana Chacon](https://netrunnerdb.com/en/card/12049) when you have 0 credits, trashing an ice with [Parasite](https://netrunnerdb.com/en/card/01012))

What about conditional abilities without specifically static conditions? Not governed by NCIGS. If you make a successful run with [DreamNet](https://netrunnerdb.com/en/card/26095) installed and no cards in the stack, the ability still triggers and draws zero cards.


## Limitations
Does NCIGS mean that I can't perform an action if some of its effects can't happen? Not quite. There's another Golden Rule in Netrunner that you always try to do as much of an effect as possible:

> **CR 1.2.4** If an instruction does not include the words “if able,” as much of that instruction as
possible is carried out. Any parts of the instruction that are not possible to carry out are
ignored.

This means that you can still play cards like Diesel even if you have only two cards left in the stack. You simply draw those two cards and you're done. NCIGS is only fulfilled if the effect wouldn't change anything at all. Thus, if you have *no* cards left in the stack, 1.2.5 overrides 1.2.4 and forbids you from playing the card.

"But hey now", you say, "I have some convoluted reason to want to get this Diesel out of my hand right now. It's important."[^2] No can do I'm afraid! Drawing 0 cards is not a change in game state [^3], and while the trashing of the event after resolving is itself clearly a change in game state, remember that the NCIGS rule only looks at the text on the card, not the framework surrounding the playing of it. "But what about [VRCation](https://netrunnerdb.com/en/card/30021)? That costs one credit to play, that's a change in game state right?" It sure is! But again, the rule doesn't care. It only looks at what the result of resolving the effect itself would be, not at costs or other effects triggering off of the paying of costs.


## Costs
This is where the fun starts. Certain cards have costs that are quite intricate. [Simulchip](https://netrunnerdb.com/en/card/26085) is the classic example. Its additional cost pulls double duty. It imposes a limitation on when the card can be used, but it can also function as an enabler for the ability itself, by trashing a program that you then immediately reinstall. How convenient!

[![Simulchip](https://static.nrdbassets.com/v1/large/26085.jpg ""If no installed programs have been trashed this turn, you must trash 1 installed program as an additional cost to use this hardware. [trash]: Install 1 program from your heap, paying 3c less."")](https://netrunnerdb.com/en/card/26085)

A typical use case is trashing a [Botulus](https://netrunnerdb.com/en/card/30004) and reinstalling it on another piece of ice. However! NCIGS demands that we look only at the results of resolving the effect of the ability when determining if the ability may be used or not. So let's look at a common game state: It's early in the game, you haven't actually trashed any cards yet; the heap is empty. You have a Botulus installed on a piece of ice in front of HQ, and a Simulchip. You run R&D, and when the corp rezzes their Ice Wall, you want to pop Simulchip to trash the Botulus and reinstall it on Ice Wall instead. But you can't. NCIGS only looks at the effect, which is to install a program from the heap. There's no program in the heap, so the effect does not have "the potential to change the game state". "But that's preposterous" you say, "obviously Botulus will be in the heap when the effect resolves and I'll be able to install it". Yes, this is obviously the case. But NCIGS doesn't care, it doesn't look at the results of paying costs. If you had some other program in the heap beforehand - a [Rezeki](https://netrunnerdb.com/en/card/26026), let's say - NCIGS agrees that the effect has the potential to change the game state, and will allow you to activate the ability. You are now free to trash Botulus and reinstall it just like you wanted. You're not required to actually install the Rezeki, it just had to be there for NCIGS to give the green light.

Simulchip is very similar to the now long rotated card [Scavenge](https://netrunnerdb.com/en/card/03034). Its original wording had the same type of additional cost language that resulted in the same kinds of locked situations where you were forbidden from playing it, with the additional complication of that card allowing you to install a program from your grip as well, so it was valid to play Scavenge with an empty heap if you had a program in your grip. How could your opponent know that this was the case? Well, they just had to trust you, or you could ask a judge to come over to look at your hand and confirm that you could legally play Scavenge. This was considered very tedious and countless players undoubtedly misplayed this interaction without ever being aware of it. Eventually, the card received errata that completely rewrote the ability to have the trashing be part of the effect instead of the cost, allowing the NCIGS rule to take it into account. This was one of very few times that FFG issued an errata to a card simply to improve the usability. In almost all other cases, errata was reserved for cards that had [omissions](https://netrunnerdb.com/en/card/04002), [misprints](https://netrunnerdb.com/en/card/10019) or (in extreme cases only) [were in dire need of rebalancing](https://netrunnerdb.com/en/card/01081).

[![Scavenge](https://static.nrdbassets.com/v1/large/03034.jpg ""As an additional cost to play this card, trash an installed program. Install a program from your grip or heap, lowering the install cost of that program by the cost of the program trashed."")](https://netrunnerdb.com/en/card/03034)

Paying costs can also be the trigger for other abilities. The most well-known examples are [Geist](https://netrunnerdb.com/en/card/08063) and [Tech Trader](https://netrunnerdb.com/en/card/10023) (often played together, now both rotated). After a cost is paid there is a checkpoint, allowing conditional abilities to trigger in between the paying of the cost and the resolution of the ability's effect. Going back to Simulchip, let's imagine we want to use it's ability to install an Engolo, a pricy card at 5 credits. It's the only card in your heap, having been trashed earlier the same turn, so there is a valid target for Simulchip. You, however, are broke. Luckily, you have two Tech Traders installed that will give you 2 credits when you trash Simulchip, and the ability itself gives you a 3 credit discount, so that should cover it! Alas, no. NCIGS ignores game state changes triggered by the paying of costs, and determines that you are 2 credits short of being able to pay for Engolo, so you can't activate the ability.

[![Geist](https://static.nrdbassets.com/v1/large/08063.jpg ""Whenever you use a [trash] ability, draw 1 card."")](https://netrunnerdb.com/en/card/08063) [![Tech Trader](https://static.nrdbassets.com/v1/large/10023.jpg ""Whenever you use a [trash] ability, gain 1 [credit]."")](https://netrunnerdb.com/en/card/10023)

## Subversion
NCIGS is not universal. It applies specifically at the point of the timing sequence where you choose to take an action, activate a paid ability or trigger a conditional ability. Once an effect has started resolving, NCIGS doesn't care anymore. This means that you can sometimes walk right past it and perform exactly the kind of "nonsense" plays the rule is seemingly designed to prevent. For example: Cards with effects directing the user to do something a certain number of times or spend a quantity of something allow you to choose the number 0[^3]. Take [Mutually Assured Destruction](https://netrunnerdb.com/en/card/33064). You are not allowed to play it unless you have at least 1 rezzed card in play. But if you do fulfill that condition, you may play it and choose to trash 0 cards. This will give the runner 0 tags and is a perfectly legal play.

[![Mutually Assured Destruction](https://static.nrdbassets.com/v1/large/33064.jpg ""As an additional cost to play this operation, spend [click] [click]. Trash any number of your rezzed cards. Give the Runner 1 tag for each card trashed this way."")](https://netrunnerdb.com/en/card/33064)

Another example: [Overclock](https://netrunnerdb.com/en/card/30029) is a very simple card. It enters play, you put some money on it and then make a run. During the run you can spend the credits. There are abilities that may prevent or forbid you from making runs though, like [Peace in Our Time](https://netrunnerdb.com/en/card/11109). Can you still play Overclock if such an ability is in effect? [Yes you can](https://twitter.com/NISEI_Rules/status/1561051928754237440). Placing credits on a card in play is a change in game state, even though you can logically conclude that nothing productive will come of it.

[![Overclock](https://static.nrdbassets.com/v1/large/30029.jpg ""Place 5 [credit] on this event, then run any server. You can spend hosted credits during that run."")](https://netrunnerdb.com/en/card/30029)

There is another type of effect which frequently trips people up, and that is increasing the strength of icebreakers. It is, in fact, completely legal to increase the strength of an icebreaker at any point, using their native pump abilities or abilities from another card (like [Takobi](https://netrunnerdb.com/en/card/21026)), even if it does you no good at all. This includes outside a run, or even on the corp's turn (which has recently become very relevant due to the interactions of cards like [Mantle](https://netrunnerdb.com/en/card/26088) and [The Twinning](https://netrunnerdb.com/en/card/33010)). An icebreaker typically retains any strength gains from abilities until the end of the current encouter[^4], but strength increases outside of runs are reverted almost immediately, in the next checkpoint[^5]. "In the next checkpoint" is not the same as "instantly" though, and such a strength increase is still considered a change in game state. This is not actually an exception to the NCIGS rule. It has to work like this, or it would be very hard indeed to use icebreakers! Consider how most icebreakers have separate abilities for breaking and increasing strength. The expected usage is to first use the strength-increasing ability, and then use the break ability once you have enough strength to interface. If increasing strength on its own was not considered a change in game state, icebreakers would be functionally unusable. (Or they would all have to be worded in ways similar to [Paperclip](https://netrunnerdb.com/en/card/11024) and [Black Orchestra](https://netrunnerdb.com/en/card/11042).)

Clearly, NCIGS can't completely protect us from using cards and abilities for no effect. It can both prevent seemingly legitimate use cases (like Simulchip switcheroos) and allow completely nonsensical plays (like playing Overclock after Peace in Our Time). Whatever is it for? Find out after this short break!


## Exceptions
The CR contains a single explicit exception to the NCIGS rule:

> **10.1.2a** The Corp can always use a purge effect, even if there are no virus counters
currently hosted on any cards. This is an exception to rule 1.2.5.

Crystal clear. This is needed because there is a class of cards with the text ["when the Corp purges virus counters, trash this"](https://netrunnerdb.com/find/?q=x%3A%22when+the+Corp+purges+virus+counters%2C+trash+this%22&sort=set&view=list&_locale=en). Why do these require an exception? That sounds like a change in game state to me! Indeed it is, but again: NCIGS is evaluated "without regard to any other abilities that may meet their conditions in the process of initiating or resolving that action or ability". It's not just costs and abilities triggered by costs that are not taken into account. Abilities triggered by the resolution of the effect itself are also ignored.[^6] So far, the various rulemakers of Netrunner have not found a better solution for this conundrum than to simply allow purging in spite of NCIGS.


## Origins
So why is NICGS important? Why do we need this inconsistent beast of a rule which only serves to confuse and perturb honest runners?

The oldest ancestor to the modern NCIGS rule can be found in [FFG FAQ 1.4](http://web.archive.org/web/20140709015052/http://www.fantasyflightgames.com/ffg_content/android-netrunner/support/FAQ/Android-Netrunner%20FAQ.pdf), from early 2014:

> **Triggering Actions**  
> A player cannot trigger an action unless he [sic] is also able to resolve it.

This was amended later the same year in [FAQ 1.5](http://web.archive.org/web/20140823130131/http://www.fantasyflightgames.com/ffg_content/android-netrunner/support/FAQ/Android-Netrunner%20FAQ.pdf) to also refer to abilities:

> **Triggering Actions and Abilities**  
> A player cannot trigger an action/ability unless he [sic] is also able to resolve it.

The fully evolved NCIGS rule was then added to the game a year later, in [FAQ 2.2](https://images-cdn.fantasyflightgames.com/filer_public/c6/40/c6409b40-6a4e-496a-ba90-9ce1bd645a13/netrunner_lcg_faq_22.pdf):

> **Triggering Actions and Abilities**  
> A player can only trigger an action or ability if its effect has the potential to change the game state. This potential is assessed without taking into account the consequences of paying play, install, or rez costs or triggering any further abilities.

This is the form it would retain for the rest of FFG:s tenure, until being replaced by NISEI:s very similar wording in [version 1.0 of the Comprehensive Rules](https://nisei.net/wp-content/uploads/2021/08/NISEI-Comprehensive-Rules-v1.0-2018-10-29.pdf).


FAQ 2.2 came out a few months after Geist was printed (but before Tech Trader), and a popular explanation is that the main reason for the expanded ruling was to prevent Geist from unduly exploiting cheap trash effects like [Fall Guy](https://netrunnerdb.com/en/card/04106) and [Shiv](https://netrunnerdb.com/en/card/08066).

Another prominent card in the same pack as Geist ([The Underway](https://netrunnerdb.com/en/set/uw/images), SanSan Cycle) was [Street Peddler](https://netrunnerdb.com/en/card/08062), for which the most common rules question always was: "If Street Peddler has only events hosted on it, can I still trash it to release them into the heap or are they stuck there forever?" By now you know enough to answer that question yourself.[^7]

[![Street Peddler](https://static.nrdbassets.com/v1/large/08062.jpg ""When you install Street Peddler, host the top 3 cards of your stack facedown on Street Peddler (you may look at these cards at any time). [trash]: Install 1 card hosted on Street Peddler, lowering its install cost by 1."")](https://netrunnerdb.com/en/card/08062)

Why didn't the designers want the player to be able to do things like this? There are two main lines of reasoning that can lead to that conclusion:
1. It's not good for balance. Geist can exploit cheap trash effects and draw way too many cards way too easily. (With the later addition of Tech Trader, which caused you to also make money from trashing your cards, this argument got even more popular.)
2. It's philosophically wrong. We want people to play cards because of what the effect of the card is, not to exploit side effects in a way that make the card effect itself secondary. That's just a design goal we have. (Consider: [Cyberdex Sandbox](https://netrunnerdb.com/en/card/26128) recently got [banned](https://nisei.net/blog/ban2208/).)

We don't have an official reason for the rule's existence, but the fact that the full rule was introduced only after Geist and Street Peddler were released could be an argument for 1). On the other hand, Geist wasn't a particularly strong ID until much later, after Tech Trader and a few other cards lifted him from obscurity. There were also the early incarnations of the rule which seem to indicate a similar intention even if they were not as precise and wide in scope, which could imply that 2) is a larger factor.

In conclusion: We don't really know.

## Alternate universes
What would happen if we just removed the NCIGS rule(s)?

There would be many small consequences, and a few larger ones. In the category of "probably fine" we have:

- You could trash your hand at will with [Citadel Sanctuary](https://netrunnerdb.com/en/card/11070).
- You could freely trash installed cards with [Endless Hunger](https://netrunnerdb.com/en/card/09033). (The similar cards [Heartbeat](https://netrunnerdb.com/en/card/09032) and [Dummy Box](https://netrunnerdb.com/en/card/12108) would not be usable for this purpose, since they are interrupts.)
- You could remove virus counters from Botulus in anticipation of the corp playing [Reverse Infection](https://netrunnerdb.com/en/card/21053).
- [24/7 News Cycle](https://netrunnerdb.com/en/card/09019) could be used with no "when scored" abilities to target just to conjure advancement counters with [Jemison Astronautics](https://netrunnerdb.com/en/card/12016) - which just turns it into a worse [Sacrifice](https://netrunnerdb.com/en/card/12039) though.
- Simulchip would finally work like people expect it to (like Scavenge after the errata).

Somewhat more spicy are these two, which could potentially be argued to be "too powerful":

- Geist could draw cards and generate money even more flexibly than is already possible, making him even more of an economic tornado as well as having improved flatline protection.
- [False lead](https://netrunnerdb.com/en/card/02080) could be used at any time (including when the runner is at 1 click, losing them 0 clicks) to place advancement counters with Jemison. In particular, this would allow you to trivially execute a [Drago](https://netrunnerdb.com/en/card/33051) + [Boom!](https://netrunnerdb.com/en/card/11058) kill combo, as long as you have a False Lead scored beforehand.

Can you come up with something worse? Let me know! [This classic Reddit thread](https://www.reddit.com/r/Netrunner/comments/4azn5d/rules_exercise_pretend_the_no_change_in_game/) didn't really produce any mindblowing examples either.

## Where we are
NCIGS is one of those perennial rules quirks that keeps vexing people to this day. Some have very strong opinions about it, while others feel it's an obvious and completely uncontroversial rule. The fact that FFG issued errata to Scavenge many years after its release just to get people to stop asking how it worked might be an indicator that there's something fundamental about NCIGS that screws with our heads somehow. Given that history, it surprised some that NISEI chose to print Simulchip, which made sure we had a reason to continue arguing about NCIGS even after Scavenge, Geist and Street Peddler had all rotated.

There is an intrinsic friction between printing cards whose costs are functionally part of their effects, and having a rule that ignores costs when evaluating whether the game state could change or not. This basic pain point is unlikely to change. However, apart from Simulchip, NISEI has printed very few cards which run directly afoul of NCIGS all on their own this way. (We'll talk about [The Class Act](https://netrunnerdb.com/en/card/26018) and its errata odyssey another time.) But Simulchip will rotate from Startup at the end of this year, and with that, at least the risk of new players getting frustrated by that particular gremlin mostly goes away. NCIGS is gradually turning into a thing of the past, right?

Well...

## A challenger appears
The new Midnight Sun ID [Ob Superheavy Logistics](https://netrunnerdb.com/en/card/26085) presents a dizzying array of entirely new ways to get confused about NCIGS! You can score the agenda [Azef Protocol](https://netrunnerdb.com/en/card/33058), paying the additional cost to trash an installed card which will trigger Ob, fetching a card to *overinstall* the Azef Protocol and... not score it. Or you can use the trash ability on [Reconstruction Contract](https://netrunnerdb.com/en/card/21020) to trigger Ob[^8], fetch a card like [Urtica Cipher](https://netrunnerdb.com/en/card/30045) and move the counters from Reconstruction Contract to it, even though it wasn't even in play when you activated the ability. Watch out though! Because there has to be *another* advanceable card installed somewhere for NCIGS to accept this. Which one? The runner will just have to trust the corp on that.

Or they could call a judge to confirm.

[![Ob Superheavey Logistics](https://static.nrdbassets.com/v1/large/33057.jpg ""Whenever you trash a rezzed card, except during installation, you may search R&D for 1 card with a printed rez cost exactly 1credit less than the trashed card's printed rez cost. Install and rez the card you found, ignoring credit costs. Use this ability only once per turn."")](https://netrunnerdb.com/en/card/26085)


### Appendix: What is the "game state" anyway?
The phrase "game state" is mentioned 33 times in the NISEI Comprehensive Rules, but none of those instances is a definition of the term. It is a concept which we have to accept a priori, and its meaning is supposedly obvious. The intuitive definition would be something like "the game state is the collection of all objects, abilities and information about current and past events and states affecting those objects and abilities relevant to the game of Netrunner currently being played". Are currently unused tokens in the supply part of the game state? The CR does define the concept of "the bank" which is a public zone where all currenly unusued tokens reside. So maybe? Does that mean that adding new tokens to the bank from outside the game is a change in game state? Cards that have been "removed from the game" are in a special zone known as the "removed-from-game zone". This is different from being "outside the game" which means not being in any zone. (Cards like [Rebirth](https://netrunnerdb.com/en/card/10083) and [DJ Fenris](https://netrunnerdb.com/en/card/22025) interact with cards "outside the game".) Is "not being in any zone" the same as not being part of the game state? No one knows.


### References
This article uses the [NISEI Comprehensive Rules Document version 1.6](https://nisei.net/wp-content/uploads/2022/07/NISEI-Comprehensive-Rules-v1.6-Clean.pdf), which was released on 22 July 2022.

**Rules mentioned:**  
*Chapter 1: Game Concepts*  
1.2.4 (p.6)  
1.2.5 (p.6)

*Chapter 3: Card Types*  
3.9.5b (p.39)  
3.9.5d (p.39)

*Chapter 5: Turns*  
5.2.4 (p.51)

*Chapter 9: Abilities*  
9.1.5b (p.85)  
9.1.6d (p.35)  
9.6.7d (p.98)  
9.12.2b (p.115)  
9.12.2d (p.116)

*Chapter 10: Additional Rules*  
10.1.2a (p.118)

**Cards mentioned:**  
[Lady](https://netrunnerdb.com/en/card/29006)  
[Scavenge](https://netrunnerdb.com/en/card/03034)  
[Diesel](https://netrunnerdb.com/en/card/31027)  
[Rejig](https://netrunnerdb.com/en/card/26029)  
[Aniccam](https://netrunnerdb.com/en/card/26084)  
[SMC](https://netrunnerdb.com/en/card/03046)  
[Corroder](https://netrunnerdb.com/en/card/31006)  
[Conduit](https://netrunnerdb.com/en/card/30024)  
[Hippo](https://netrunnerdb.com/en/card/21103)  
[Dadiana Chacon](https://netrunnerdb.com/en/card/12049)  
[Parasite](https://netrunnerdb.com/en/card/01012)  
[DreamNet](https://netrunnerdb.com/en/card/26095)  
[VRCation](https://netrunnerdb.com/en/card/30021)  
[Simulchip](https://netrunnerdb.com/en/card/26085)  
[Botulus](https://netrunnerdb.com/en/card/30004)  
[Rezeki](https://netrunnerdb.com/en/card/26026)  
[Scavenge](https://netrunnerdb.com/en/card/03034)  
[Pawn](https://netrunnerdb.com/en/card/04002)  
[Museum of History](https://netrunnerdb.com/en/card/10019)  
[AstroScript Pilot Program](https://netrunnerdb.com/en/card/01081)  
[Geist](https://netrunnerdb.com/en/card/08063)  
[Tech Trader](https://netrunnerdb.com/en/card/10023)  
[Mutually Assured Destruction](https://netrunnerdb.com/en/card/33064)  
[Overclock](https://netrunnerdb.com/en/card/30029)  
[Peace in Our Time](https://netrunnerdb.com/en/card/11109)  
[Takobi](https://netrunnerdb.com/en/card/21026)  
[Mantle](https://netrunnerdb.com/en/card/26088)  
[The Twinning](https://netrunnerdb.com/en/card/33010)  
[Paperclip](https://netrunnerdb.com/en/card/11024)  
[Black Orchestra](https://netrunnerdb.com/en/card/11042)  
[Fall Guy](https://netrunnerdb.com/en/card/04106)  
[Shiv](https://netrunnerdb.com/en/card/08066)  
[Street Peddler](https://netrunnerdb.com/en/card/08062)  
[Cyberdex Sandbox](https://netrunnerdb.com/en/card/26128)  
[Citadel Sanctuary](https://netrunnerdb.com/en/card/11070)  
[Endless Hunger](https://netrunnerdb.com/en/card/09033)  
[Heartbeat](https://netrunnerdb.com/en/card/09032)  
[Dummy Box](https://netrunnerdb.com/en/card/12108)  
[Reverse Infection](https://netrunnerdb.com/en/card/21053)  
[24/7 News Cycle](https://netrunnerdb.com/en/card/09019)  
[Jemison Astronautics](https://netrunnerdb.com/en/card/12016)  
[Sacrifice](https://netrunnerdb.com/en/card/12039)  
[False lead](https://netrunnerdb.com/en/card/02080)  
[Drago](https://netrunnerdb.com/en/card/33051)  
[Boom!](https://netrunnerdb.com/en/card/11058)  
[The Class Act](https://netrunnerdb.com/en/card/26018)  
[Ob Superheavy Logistics](https://netrunnerdb.com/en/card/26085)  
[Azef Protocol](https://netrunnerdb.com/en/card/33058)  
[Reconstruction Contract](https://netrunnerdb.com/en/card/21020)  
[Urtica Cipher](https://netrunnerdb.com/en/card/30045)  
[Rebirth](https://netrunnerdb.com/en/card/10083)  
[DJ Fenris](https://netrunnerdb.com/en/card/22025)  
[Bloo Moose](https://netrunnerdb.com/en/card/12089)  
[Rashida Jaheem](https://netrunnerdb.com/en/card/21080)  
[NGO Front](https://netrunnerdb.com/en/card/21039)  

**Other:**  
[The Underway](https://netrunnerdb.com/en/set/uw/images), pack in the SanSan Cycle  
[Netrunner Rules team](https://twitter.com/NISEI_Rules/status/1561051928754237440), Twitter account  
[Cards that are trashed on purge](https://netrunnerdb.com/find/?q=x%3A%22when+the+Corp+purges+virus+counters%2C+trash+this%22&sort=set&view=list&_locale=en)  
[Android: Netrunner FAQ v1.4](http://web.archive.org/web/20140709015052/http://www.fantasyflightgames.com/ffg_content/android-netrunner/support/FAQ/Android-Netrunner%20FAQ.pdf)  
[Android: Netrunner FAQ v1.5](http://web.archive.org/web/20140823130131/http://www.fantasyflightgames.com/ffg_content/android-netrunner/support/FAQ/Android-Netrunner%20FAQ.pdf)  
[Android: Netrunner FAQ v2.2](https://images-cdn.fantasyflightgames.com/filer_public/c6/40/c6409b40-6a4e-496a-ba90-9ce1bd645a13/netrunner_lcg_faq_22.pdf)  
[NISEI Comprehensive Rules 1.0](https://nisei.net/wp-content/uploads/2021/08/NISEI-Comprehensive-Rules-v1.0-2018-10-29.pdf)  
[NISEI Standard Ban List 22.08](https://nisei.net/blog/ban2208/)  
[Magical Netrunner](https://www.reddit.com/r/Netrunner/comments/4azn5d/rules_exercise_pretend_the_no_change_in_game/), Reddit thread

### Acknowledgements
Vigeous - beta reading  
Ensu, nicemoreoften - alternate universe brainstorming  
HOPEFULLY OTHERS - proofreading/factchecking

### Footnotes
[^1]: A "static condition" continuously checks for a certain state, as opposed to a "trigger condition", which is listening for a particular event to occur.

[^2]: Maybe you're running [Bloo Moose](https://netrunnerdb.com/en/card/12089) and have already removed all the cards in your heap from the game. Getting one more card in there in order to get 2c at the beginning of your next turn is absolutely critical to your game plan and clicking for credits will just not be enough.

[^3]: ***CR 9.12.2b*** *Some abilities calculate a quantity using phrases like “for each”, “for every”, or “plus”. When a quantity is calculated this way for any of the purposes listed in rule 9.12.2c[^9], the resulting effect is aggregated to the value that was calculated. Only a single instance of that effect takes place. If the calculated value is less than or equal to 0, the effect does not take place at all.*

[^4]: ***CR 3.9.5b*** *Paid abilities on an icebreaker that modify that icebreaker’s strength implicitly have a duration of “for the remainder of the current encounter”.*

[^5]: ***CR 3.9.5d*** *If an icebreaker’s paid ability modifies its strength outside of an encounter and does not specify another applicable duration, the modification expires during the next checkpoint.*

[^6]: The removal of virus counters is an explicit part of the purging effect itself, not a triggered ability, and thus passes the NCIGS test.

[^7]: They are stuck there forever.

[^8]: Reconstruction Contract would be another example to bring up in our NCIGS-free alternate universe; it could be used as a pure tutor card in Ob, fetching sweet 0 cost cards like [Rashida Jaheem](https://netrunnerdb.com/en/card/21080) and [NGO Front](https://netrunnerdb.com/en/card/21039) without having to put in the work of doing meat damage to put counters on it first.

[^9]: ***CR 9.12.2c*** *The following effects are aggregated when performed in a single instruction, as described in rule 9.12.2b[^3]: gaining, losing, or spending a number of credits; gaining, losing, or spending a number of clicks; taking, removing, or preventing a number of tags; taking, removing, or preventing a number of bad publicity; looking at or revealing a number of cards from a specified location; drawing a number of cards; trashing a number of cards from specified locations (including by damage); and shuffling a number of cards from a player's discard pile into their deck.*
