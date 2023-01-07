---
layout: post
title:  "The Parhelion unofficial comprehensive release notes I: Rules"
date:   2023-01-07 22:00:00
categories: release-notes
tags: [cr, cr-1.5, cr-1.6, cr-22.12]
---

*Sifting through the CR with a fine-toothed comb so you don't have to.*

On December 9 NSG released their newest expansion for Netrunner, Parhelion, and with it a new version of the Comprehensive Rules. More recently, on December 20, an updated Card Text Updates document was released as well. As of the publication of this article, no card rulings have been released on NRDB yet, but they are expected to arrive in the near future.

In total, three pages of rules have been added, putting the page count of the CR now at 133 pages in total. The CR itself doesn't contain a lot of context for why these changes were made and what their implications are, and that's is what I will attempt to address in this article.

The changes are split into three categories: "Major", "Minor" and "Interesting". Major changes are things that will directly affect how we play the game on a regular basis, and minor changes do not. Interesting changes are minor changes that I wanted to blather about a bit.

Rules text excerpts are provided for all changes, with the specific words that were added/removed/changed highlighted. In cases with only additions, the old text is omitted.

Changes to examples are not covered by this article. Several of the new rules come with examples, and some changed rules have had new examples added or changed. In two instances, examples received a wording update where some lingering mentions of the old term "brain damage" were replaced with "core damage". These examples were referencing cards which had not yet received text updates when CR 1.6 was released. (As of the release of Midnight Sun, only new cards used "core damage". Changes to the official card text of older cards to use "core damage" weren't made until the most recent Card Text Updates document, released with Parhelion.)

### Contents
- [What you need to know](#what-you-need-to-know)  
- [Version what?](#version-what)
- [Major changes](#major-changes)
- [Interesting changes](#interesting-changes)
- [Minor changes](#minor-changes)

> **Update 2023-01-07** 
- Clarified the ZATO City Grid server reference explanation.

## What you need to know
To make things simpler for those who just want to know how the new rules affect their everyday lives, I've collected the major takeaways here at the top.

- [9.12.1e](#9121d-e---expanded) - [Hush](https://netrunnerdb.com/en/card/33071) beats [Magnet](https://netrunnerdb.com/en/card/10103).
- [1.13.6c](#1136a-b-c-d---expanded) - The order of runner cards installed facedown is open information, similar to how unrezzed cards in a remote are treated. (Facedown non-installed cards can be secretly reordered to your heart's content though.)
- [1.13.11](#11311---expanded) - Moving a card between zones always results in all hosted objects being trashed. (Including, possibly, swapping agendas between score areas. There's currently a conflict between two rules in that particular situation. Judges, be aware!)
- [2.16.7h](#2167c-h-i---subtypes-added--removed) - The "bomb" subtype has been completely removed and subsumed by the "weapon" subtype.
- [4.6.6i](#466g-i-j---expanded) - The meaning of "this server" on ice subroutines is *archives* when being fired by [Nanisivik Grid](https://netrunnerdb.com/en/card/33111).
- [4.6.6j](#466g-i-j---expanded) - The meaning of "this server" on ice subroutines is *the server the ice was trashed from* when being fired by [ZATO City Grid](https://netrunnerdb.com/en/card/33127).
  - No other effects use this time travel logic - abilities on ice that count hosted counters or installed cards still do these checks after the ice has been trashed by ZATO.
- [8.5.14](#8514---added) - The meaning of positional references like "directly inward" on ice subroutines is *undefined* when being fired by Nanisivik Grid or ZATO City Grid, and effects that rely on them fail to resolve.
- [4.8.7](#487---added) - It is finally, 100%, definitely, unambiguously clear that you do not need to tell the runner which card you put on the bottom of R&D with [Daily Business Show](https://netrunnerdb.com/en/card/06086). (But the reverse is still true of [Blueberry Diesel](https://netrunnerdb.com/en/card/26012) and [The Class Act](https://netrunnerdb.com/en/card/26018).)
- [9.8.2b](#982b---reworded) - Abilities that cause ice to gain additional subroutines are applied in chronological order.
- [9.8.10](#9810---added) - The source object for the replacement subroutine from [Tsakhia "Bankhar" Gantulga](https://netrunnerdb.com/en/card/33074) is considered to be the ice, not Bankhar herself. This means that [Persephone](https://netrunnerdb.com/en/card/12042) and [Chief Slee](https://netrunnerdb.com/en/card/11077) both work as you might intuitively expect.
- [9.12.2e](#9122e---expanded) - Any X that can't be resolved is considered to be 0, always.
- [10.1.5](#1015---moved--modified) - [Media Blitz](https://netrunnerdb.com/en/card/09021) works with all self-references now. Rejoice!

[![Hush](https://static.nrdbassets.com/v1/large/33071.jpg)](https://netrunnerdb.com/en/card/33071)
[![Media Blitz](https://static.nrdbassets.com/v1/large/09021.jpg)](https://netrunnerdb.com/en/card/09021)

## Version what?
That's right! One of the changes this time is the versioning format of the document itself. The Comprehensive Rules are now versioned on the format [year].[month], the same scheme as the Standard Ban list. While I personally like the clarity of "1.6", "1.7", etc, I accept the logic of different parts of NSG using the same versioning system for their documents.

## Major changes
#### 4.6.6g, i, j - EXPANDED
> **[CR 1.6](/cr/1.6.html#pf2e)**  
> g. Only **one** region upgrade can be installed in the root of a server at a time. See
section 3.6.5.

> **[CR 22.12](/cr/22.12-Annotated.html#pf2f)**  
> g. Only **1** region upgrade can be installed in the root of a server at a time. See section
3.6.5.  
>
> **i. Some cards refer to the server where they are located (or the central server corresponding to the zone where they are located) using the phrase “this server”. If an ability is initiated by a trigger condition or cost involving the ability’s source card moving from a server, its root, or protecting it to another server or to a location not associated with any server, treat “this server” as referring to the server associated with the previous location of the card throughout resolution of that ability. If an ability moves its source card while it is resolving, continue to interpret “this server” based on the card’s previous location.**
>
> **j. If an ability on a card currently or previously located in a server, its root, or protecting it  refers to “another server”, this means any server except “this server” as interpreted by rule 4.6.6i. If a card’s abilities involve choosing a server, “another server” in a linked ability means any server except the chosen server. If neither of the previous cases apply and a run is in progress, “another server” means any server except the attacked server.**

This is an important addition that ensures that the new cards ZATO City Grid and Nanisivik Grid function as intended. Both of them have the ability to fire subroutines on pieces of ice, and in both cases the ice cards are in archives when the ability resolves.

The implication of this rule is that the location of the ice card is the determinator for location references like "this server" or "another server". For Nanisivik, this means that all such references will be to archives. For ZATO though, the second sentence of this rule results in the game remembering where the ice was when it was trashed as the cost to use the ZATO ability. This is typically the server being run, but there are exotic scenarios with cards like [Konjin](https://netrunnerdb.com/en/card/26109) that cause you to encounter ice on other servers, in which case a ZATO installed on that other server may come into play.

Note that this "memory effect" isn't a general principle, it's only used specifically when resolving server references. If ZATO fires a sub on [Surveyor](https://netrunnerdb.com/en/card/21118) for example, X is resolved by counting the ice protecting the server at the time the ability resolves - that is without counting Surveyor, which is not installed in front of that server anymore. Also, if used with an advanceable ice like [Colossus](https://netrunnerdb.com/en/card/13048), the ability does not "remember" any advancement counters that were removed when the ice was trashed.

This rule also affects some older cards like [Warroid Tracker](https://netrunnerdb.com/en/card/12068) whose abilities trigger from themselves being trashed, and where the exact meaning of "this server" was previously somewhat nebulous (since the card is technically in archives when the ability resolves). That is no longer the case: "This server" in the text of Warroid Tracker now unambiguously refers to the server where it was installed before being trashed, as one would expect.

[![ZATO City Grid](https://static.nrdbassets.com/v1/large/33127.jpg)](https://netrunnerdb.com/en/card/33127)
[![Nanisivik Grid](https://static.nrdbassets.com/v1/large/33111.jpg)](https://netrunnerdb.com/en/card/33111)

#### 4.8.7 - ADDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf32)**  
> **Facedown cards in the set-aside zone must be kept in distinct groups according to the effect that sets them aside. Cards within such a group are not ordered and can be freely arranged by their controller.**

This new rule finally lays to rest the age-old debate about whether you need to reveal which card you moved to the bottom of R&D when using Daily Business Show: You don't. The cards you look at are set aside facedown as a group, and such groups can be secretly reordered at will.

But wait! Doesn't Daily Business Show just say "/.../ increase the number of cards you will draw by 1. When you draw those cards, add 1 of them to the bottom of R&D"? There's nothing about setting aside in there! Well, this is where it is important to remember that as per rule 8.4 (added in CR 1.5), the definition of "drawing a card" in Netrunner is: "To draw 1 or more cards, a player *sets aside* that many cards from the top of their deck facedown. The cards are then considered drawn, and abilities with trigger conditions related to cards being drawn can act on them. When resolving any such abilities is complete, the set-aside cards are added to their owner’s hand."

Maybe counterintuitively, this rule does not apply to the two well-known cards similar to Daily Business Show, Blueberry Diesel and The Class Act. Those both say "look at" the top cards of your stack, after which you may move one of them to the bottom. Merely looking at cards does not move them anywhere, so in these cases, you *are* required to let your opponent know which one you put on the bottom.

[![Daily Business Show](https://static.nrdbassets.com/v1/large/06086.jpg)](https://netrunnerdb.com/en/card/06086)
[![The Class Act](https://static.nrdbassets.com/v1/large/26018.jpg)](https://netrunnerdb.com/en/card/26018)

#### 9.8.10 - ADDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf6a)**  
> **One card, Tsakhia "Bankhar" Gantulga, can apply a replacement effect while a subroutine is imminent in order to resolve a different subroutine instead. The replaced subroutine is treated as having the same source as the original imminent subroutine.**

The CR has a storied history of handling some problematic cards explicitly rather than trying to collect them under the general rules umbrella. Most of the time, these are legacy FFG cards with quirky wordings or exotic effects that don't really fit the mold. In this rare example of a completely new card getting this treatment, Tsakhia "Bankhar" Gantulga gets its own rule to sort out which card is to be considered the source for the special replacement subroutine.

Bankhar is a type of effect we haven't seen before, where the resolution of an ability (a subroutine) is replaced by another one. While the replacement subroutine isn't technically "gained" by the ice card itself, the ice is considered the source of it, not Bankhar. This might not be obvious from reading the card text itself, which is why it got its own bespoke rule in the CR.

This is a concept that I could imagine seeing expanded into a general rule in the future, if more cards with this type effect are to be printed. But for now, the rules team are opting not to create entirely new rules spaces to support a single card.

As the example in the CR mentions, this nuance does matter for cards like Persephone. Is it finally her time to shine?[^1]

The rule formerly known as 9.8.10, "Steps of Resolving a Subroutine" is now rule 9.8.11.

#### 9.12.1d, e - EXPANDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf74)**  
> **d. If a static or lingering effect changes whether a second effect is active, what objects it applies to, or what it does to those objects, the second effect DEPENDS ON the first effect. To determine the characteristics of each object in a game state where dependencies exist, use the following process: begin with each object’s printed characteristics. Then, apply effects that modify objects to the game state in the order specified by rule 9.12.1e. Do not apply an effect if it originates from a static ability that is no longer present or no longer active due to a previously-applied effect. When all active effects are applied, this process is complete and each object has its correct characteristics.**
>
> **e. When applying effects as indicated by rule 9.12.1d, an effect that is waiting to be applied is INDEPENDENT if it does not depend on any other effects waiting to be applied. Always choose an independent effect as the next effect to apply, if possible. If there are multiple independent effects at once, those effects can be applied in any order relative to each other. (The order chosen should have no impact on the ultimate result.) If there are no independent effects (because each remaining effect depends on another, forming a "loop"), check the source of each of those effects, and treat effects from hosted objects as if they did not depend on effects from the objects they are hosted on.**

This rule about simultaneous effects has been greatly expanded to accomodate the new card Hush. It defines an entirely new system for ordering static or lingering effects that are in conflict with each other. Effects whose behavior (or existence) could potentially be modified by another effect "depend on" that other effect and should always be applied after it. In most cases, this is rather straightforward, as shown by this example from the CR that I'm shamelessly borrowing:

---

The situation: [Warden Fatuma](https://netrunnerdb.com/en/card/21093), [Mother Goddess](https://netrunnerdb.com/en/card/06010), Hush and [Ansel 1.0](https://netrunnerdb.com/en/card/30038) ~~walk into a bar~~ are all installed. Hush is hosted on Mother Goddess.

*Step 1*  
Warden Fatuma **depends on** Mother Goddess  
Mother Goddess **depends on** Hush  
Hush **is independent**  
Ansel **has no effect to apply**

Hush is applied: Mother Goddess is blanked.

*Step 2*  
Warden Fatuma **is independent**  
Mother Goddess **has no effect to apply**  
Ansel **has no effect to apply**

Warden Fatuma is applied: Ansel gains a subroutine (but Mother Goddess does not, not being a bioroid).

*Step 3*  
Mother Goddess **has no effect to apply**  
Ansel **has no effect to apply**

No further actions to take.

---

Note that it is the individual effects that are applied in this process, not the card as a whole. It is conceivable that a card with multiple abilities could get involved in a dependency chain like this, where the different abilities on the card could depend on various other effects and need to be handled individually when resolving the chain.

[![Mother Goddess](https://static.nrdbassets.com/v1/large/06010.jpg)](https://netrunnerdb.com/en/card/06010)
[![Magnet](https://static.nrdbassets.com/v1/large/10103.jpg)](https://netrunnerdb.com/en/card/10103)

It's not always a straight line though. There's a by now well-known example of a dependency loop, which is also covered by this new rule, with an explicit example given. In such situations, effects whose source is hosted on the source of other effects take precedence:

---

The situation: Hush is installed on Magnet.

*Step 1*  
Magnet **depends on** Hush  
Hush **depends on** Magnet

There's a dependency loop, so hosted objects take precedence.

Hush is applied: Magnet is blanked.

*Step 2*  
Magnet **has no effect to apply**

No further actions to take.

---

#### 10.1.5 - MOVED & MODIFIED
> **[CR 1.6](/cr/1.6.html#pf7e)**  
> **10.14.1. If the card name referenced on a card matches the name of that card, and the reference is not plural and/or does not include an additional modifier (e.g., “other copies” or “all”), then the card name only refers to that copy of the card, and not to any other copies of it.**
>
> **10.14.2. If a card copies the text of another card, and the copied text includes a self-reference, the copied text does not function unless it explicitly says so.**

> **[CR 22.12](/cr/22.12-Annotated.html#pf79)**  
> **10.1.5. Some cards are written with self-referential language. If a card references its own name without using the word “copy”, treat that name as if it said “this object”.**

Finally, the Rules Gods have seen fit to reward the astute reader with some new fun interactions! Rule 10.14 about self-references has been moved and reworded to be more concise and general. While before there was some quirkiness with cards referencing themselves with their printed names, all such references should henceforth be treated as if they said "this object". This means that the rules text required to handle these cards is much shorter (I approve!) and, of more interest to the janksters out there, that certain interactions which didn't work under the old rules are now enabled. Most prominently, Media Blitz now functions as you'd expect when copying cards like [Private Security Force](https://netrunnerdb.com/en/card/01107), something which explicitly didn't work before.

## Interesting changes
#### 1.13.1a - ADDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf10)**  
> **a. Only cards in score areas and the play area can host objects.**

This rule had a subclause added which specifies that only cards in score areas and the play area can host objects. This is part of the revisions made to clarify the behavior of Nanisivik and ZATO; since cards in discard piles are not in the play area, [Free Lunch](https://netrunnerdb.com/en/card/12035) and similar cards are unable to get counters from subroutines fired by the two new grids.

NOTE: In my [preview article](/news/parhelion-preview) for Parhelion, it was stated that in the current draft of the rules at that point, putting counters on ice in archives was a technically legal play, even though those counters would then immediately be removed in the next checkpoint. We can see here though that the rules team eventually decided against leaving that little tear in the rules-time continuum open.

#### 1.13.6a, b, c, d - EXPANDED
> **[CR 1.6](/cr/1.6.html#pf11)**  
> Unless otherwise **noted**, a card that is hosted **as** it is installed is hosted onto the destination card in the same faceup or facedown status it would normally be installed in.

> **[CR 22.12](/cr/22.12-Annotated.html#pf11)**  
> **Cards can be hosted faceup or facedown.**
>
> **a.** Unless otherwise **specified**, a card that is hosted **while** it is **being** installed is hosted onto the destination card in the same faceup or facedown status it would normally be installed in.
>
> **b. Unless otherwise specified, a card that is hosted without being installed is hosted faceup.**
>
> **c. Like other facedown installed cards, installed cards hosted facedown are distinct. The order in which they were installed (or turned facedown) is open information.**
>
> **d. Cards hosted facedown without being installed must be kept in distinct groups according to their host. Cards within such a group are not ordered and can be freely arranged by their controller.**

This previously rather short rule has been expanded to further elaborate on the nuances of hosted cards being faceup or facedown. This is part of the general overhaul of facedown and other hidden cards.

Of interest here is that it's now explicit that the order that facedown cards were installed or turned facedown is open information, similar to how cards in a remote server are treated. Cards hosted facedown without being installed, however, are not ordered and can be reordered freely.

#### 1.13.11 - EXPANDED
> **[CR 1.6](/cr/1.6.html#pf12)**  
> If a host card **is uninstalled**, all objects hosted on that card (and all objects hosted on those objects, and so on) are trashed during the next checkpoint. This cannot be prevented. See section 10.3 for details on checkpoints.

> **[CR 22.12](/cr/22.12-Annotated.html#pf12)**  
> If a host card **changes zones**, all objects hosted on that card (and all objects hosted on those objects, and so on) are trashed during the next checkpoint. This cannot be prevented. See section 10.3 for details on checkpoints.

The scope of this rule has expanded slightly. Now, this covers cards changing zones for any reason, not just uninstalling.

NOTE: The intention here just seems to have been to make the rule more general, but it does have one side effect: Rule 8.8.4c explicitly states that agendas with counters that are swapped between the two score areas retain all counters. This is now in direct contradiction with 1.13.11, which removes counters on any zone change. The rules team confirmed that this was an oversight when I reached out to them, and I assume that this ambiguity will be resolved in a future update. They did not state which rule should take precedence in the meanwhile though, so if this one comes up in a tournament it will be up to the judge to decide. It should be a pretty rare occurrence though, since you need a combination of several cards like [Turntable](https://netrunnerdb.com/en/card/08043) and [Exchange of Information](https://netrunnerdb.com/en/card/10092) to make this matter.

[![Turntable](https://static.nrdbassets.com/v1/large/08043.jpg)](https://netrunnerdb.com/en/card/08043)
[![Exchange of Information](https://static.nrdbassets.com/v1/large/10092.jpg)](https://netrunnerdb.com/en/card/10092)

#### 2.16.7c, h, i - SUBTYPES ADDED & REMOVED
> **[CR 1.6](/cr/1.6.html#pf21)**  
> h. The hardware subtypes are **Bomb**, Chip, Companion, Console, Consumer-grade, Cybernetic, Gear, Link, Mod, Stealth, Vehicle, and Weapon.

> **[CR 22.12](/cr/22.12-Annotated.html#pf21)**  
> c. The asset subtypes are **Academic**, Advertisement, Alliance, Ambush, Beanstalk, Bioroid, Cast, Character, Clone, Corporation, Executive, Facility, Government, Hostile, Illicit, Industrial, Political, Psi, Region, Research, Ritzy, Seedy, and Transaction.
>
> h. The hardware subtypes are Chip, Companion, Console, Consumer-grade, Cybernetic, Gear, Link, Mod, Stealth, Vehicle, and Weapon.
>
> i. The program subtypes are AI, Caïssa, Cloud, Daemon, Decoder, **Deep Net**, Deva, Fracter, Icebreaker, Killer, Stealth, **Trojan**, Virus, and Weapon.

One of the least dramatic changes, but certainly of interest to some, the three new subtypes Academic (for assets), Deep Net and Trojan (for programs) were added. Also pour one out for our dearly departed hardware subtype Bomb, which will henceforth be covered by the Weapon subtype (card text updates to [all older cards](https://netrunnerdb.com/en/card/10020) with the Bomb subtype have been [issued](https://nullsignal.games/wp-content/uploads/2022/12/Null-Signal-Games-Netrunner-Card-Text-Updates-v22.12.pdf)).

#### 8.1.4a, b - REVISED
> **[CR 1.6](/cr/1.6.html#pf4a)**  
> b. **The Runner can look at their facedown cards at any time.**

> **[CR 22.12](/cr/22.12-Annotated.html#pf4b)**  
> a. **Installed** Runner cards that are facedown do not have a name, type, or subtypes, and their abilities are not active.
>
> b. **Facedown installed Runner cards are distinct. The origin of each such card (when and how it was installed facedown, or what faceup installed card was turned facedown) is open information.**

The general rules for facedown runner cards have been expanded to handle hosted but not installed facedown cards in more detail. A subtle change here is that previously, all facedown runner cards lacked name, abilities and other features. In CR 22.12 however, this only applies to *installed* facedown cards. That is, hosted facedown cards retain all their text and abilities (though they are still inactive). This makes it more obvious how cards like Matryoshka and Street Peddler can actually function, since they reference various features of their hosted cards.

This section also repeats the information from 1.13.6 about the order of installed facedown runner cards being open information. The removed text about how the runner may look at their facedown cards, was already covered by rule 1.21.2a[^2] and thus redundant.

#### 9.1.8g - EXPANDED
> **[CR 1.6](/cr/1.6.html#pf56)**  
> g. If an active card **is trashed**, an ability of that card with a trigger condition that is met by this **trashing** remains active in **its owner’s discard pile** until any corresponding instances of the ability resolve. See rule 9.6.2 for information about instances of conditional abilities.

> **[CR 22.12](/cr/22.12-Annotated.html#pf58)**  
> g. If an active card **moves to a zone where it is inactive**, an ability of that card with a trigger condition that is met by this **zone change** remains active in **the card’s new location** until any corresponding instances of the ability resolve. See rule 9.6.2 for information about instances of conditional abilities.

This is a subtle but important update to the rules about when inactive cards have active abilities. Previously 9.1.8g only governed cards that were removed from play through trashing, but now it applies universally to any movement of cards to inactive zones. This is especially important to [Nanuq](https://netrunnerdb.com/en/card/33088) (which is also mentioned in a new example added to this section), which has a restriction which would be very leaky under the old rules. There are still a couple of ways to work around it though: If you turn it facedown with [Apocalypse](https://netrunnerdb.com/en/card/09030) and then trash it, the ability isn't active and won't trigger. You can also blank it with [Dr. Lovegood](https://netrunnerdb.com/en/card/09042), if you expect an agenda score/steal that turn (but will obviously not be able to use Nanuq that turn either). Finally, you can delay scoring agendas by trashing them with [Imp]() or [Stargate](), though that will obviously also give the corp a chance to rescue the agendas with [Spin Doctor](https://netrunnerdb.com/en/card/30053) or similar.

Amusingly, this change causes [Muertos Gang Member](https://netrunnerdb.com/en/card/08068) and [DJ Fenris](https://netrunnerdb.com/en/card/22025) to actually work. Under the old wording, their "when uninstalled" abilities would technically have been inactive and never resolved.

[![Muertos Gang Member](https://static.nrdbassets.com/v1/large/08068.jpg)](https://netrunnerdb.com/en/card/08068)
[![DJ Fenris](https://static.nrdbassets.com/v1/large/22025.jpg)](https://netrunnerdb.com/en/card/22025)

#### 9.8.2b - REWORDED
> **[CR 1.6](/cr/1.6.html#pf65)**  
> Subroutines **are the only abilities that are ordered**.  
> /.../  
> b. Unless otherwise **stated**, subroutines a piece of ice gains from an ability are added after all other subroutines the ice has at **that time**.

> **[CR 22.12](/cr/22.12-Annotated.html#pf58)**  
> Subroutines **always have a specified order**.  
> /.../  
> b. Unless otherwise **specified**, subroutines a piece of ice gains from an ability are added after all other subroutines the ice has at **the time that ability begins to apply to that ice**.

This is mostly just a rewording for clarity. The new text makes it more explicit that subroutines added by abilities are in fact chronologically ordered. That is, if multiple abilities are granting the same piece of ice new subs, the order of those subs is determined by the order in which the effects of the abilities became active. This could come into play if someone put [Wetwork Refit](https://netrunnerdb.com/en/card/11071) and Warden Fatuma in the same deck, for example[^3].

In our correspondence, the rules team did say that they want to revisit this one in the future, to make it more simple. 

#### 9.10.3b - REVISED
> **[CR 1.6](/cr/1.6.html#pf6e)**  
> Some lingering effects maintain a choice that a player made while resolving an ability in
order for another ability or effect with the same source object to make use of that choice.
>
> a. If the choice is only referred to by another lingering effect, the lingering effect
maintaining the choice has the same duration as the other lingering effect.
>
> b. If **the abilities linked in this way use the word “this” in reference to a timing structure, then the reference applies only to the occurrence of that timing structure in which the choice was made. In this case**, the duration of the lingering effect maintaining the choice expires when that **timing structure** ends or the source object becomes inactive.

> **[CR 22.12](/cr/22.12-Annotated.html#pf70)**  
> b. If **a conditional ability has a “when your turn begins” trigger condition and no effects other than making a choice**, the duration of the lingering effect maintaining the choice expires when that **turn** ends or the source object becomes inactive.

In this rare case of reducing the scope of an existing rule, the previous - rather convoluted - system of linked lingering abilities is replaced by a more concrete wording that simply states that certain types of abilities expire at the end of your turn. This rule was only used for turn-scope effects like [Security Testing](https://netrunnerdb.com/en/card/05048) anyway, so the added complexity just wasn't needed. Some other similar abilities such as [Net-Ready Eyes](https://netrunnerdb.com/en/card/08047) are fully covered by 9.10.3a and are not affected by this change.

[![Security Testing](https://static.nrdbassets.com/v1/large/05048.jpg)](https://netrunnerdb.com/en/card/05048)
[![Net-Ready Eyes](https://static.nrdbassets.com/v1/large/08047.jpg)](https://netrunnerdb.com/en/card/08047)

#### 9.12.2e - EXPANDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf76)**  
> **e. Some values are defined with a variable “X”. If the ability defining X is inactive or if the value of X cannot be evaluated, treat X as equal to 0.**

It was already established (by rule 1.16.2c,d) that install costs of "X" are treated as 0 when referenced by other abilities outside of installation. This new general rule expands this logic to apply to all situations where a value is defined as "X" (such as the strength of Surveyor). If X can't be determined for any reason, it's 0. Most people probably already assumed this to be the case, but it wasn't explicitly codified in the CR until now. It has become newly relevant with the introduciton of Nanisivik Grid and ZATO City Grid which both cause ice subroutines to be resolved when the ice is not installed, which causes several cards with "X" values to have new behaviors.

## Minor changes
#### 1.8.4a, b - REVISED
> **[CR 1.6](/cr/1.6.html#pfa)**  
> Cards that are INACTIVE are unable to affect the game or have most of their abilities used.
>
> a. Cards are inactive in R&D, HQ, Archives, the heap, the grip, the stack, the Runner’s score area, while set aside, and while removed from the game. **Cards installed facedown** are also inactive.
>
> b. Inactive cards in most zones retain their printed characteristics (name, card type, faction, cost, subtypes, influence, etc). **Runner cards installed facedown** have no characteristics.

> **[CR 22.12](/cr/22.12-Annotated.html#pfa)**  
> a. Cards are inactive in R&D, HQ, Archives, the heap, the grip, the stack, the Runner’s score area, while set aside, and while removed from the game. **Facedown cards in the play area** are also inactive.
>
> b. Inactive cards in most zones retain their printed characteristics (name, card type, faction, cost, subtypes, influence, etc). **Facedown installed** Runner cards have no characteristics.

This core rule listing under which circumstances cards are inactive has been updated to say that all facedown cards in the play area are inactive, where it previously only specified that *installed* facedown cards are inactive. This affects the new card [Matryoshka](https://netrunnerdb.com/en/card/33094), but also makes it clearer how cards like [Street Peddler](https://netrunnerdb.com/en/card/08062) and [Bookmark](https://netrunnerdb.com/en/card/08106) work.

#### 1.13.5 - REVISED
> **[CR 22.12](/cr/22.12-Annotated.html#pf11)**  
> Any card **in an eligible location** can act as a host, but a host relationship can only be created or permitted by a card ability.

This rule was changed slightly to take the updated 13.1a into account.

#### 1.13.12 - ADDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf12)**  
> **Condition counters are the only type of counter that can host other objects. Hosting on condition counters follows the same rules as hosting on cards.**

A new rule was added which states that condition counters are the only type of counter that can host other objects. It does not change the behavior of any existing cards, but serves to codify that [Rover Algorithm](https://netrunnerdb.com/en/card/12100) is allowed to exist, while making it clear that all host objects are by definition cards, allowing other rules related to hosting to be worded accordingly.

#### 1.21.1b - EXPANDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf1c)**  
> **b. Some effects host multiple cards on an object at the same time or set aside multiple cards at the same time. Facedown cards that enter a zone at the same time by the same effect are treated as a group. See section 1.13.6 and rule 4.8.7, respectively.**

This is just a reference to two other modified/added rules, which are both concerned with the new concept that facedown cards are treated as a group under some circumstances.

#### 4.2.3a - EXPANDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf2a)**  
> **a. While searching a deck, a player is not required to maintain the order of the searched cards or indicate the previous location of any card found by the search. Note that the deck is always shuffled upon completion of the search, as required by rule 8.7.3.**

Just an added clarification that a player does not have to maintain or reveal any information when searching a deck.

#### 4.6.2 - REVISED
> **[CR 1.6](/cr/1.6.html#pf10)**  
> The number of cards in the play area and **where in the play area they are located** is always open information.

> **[CR 22.12](/cr/22.12-Annotated.html#pf2d)**  
> The number of cards in the play area and **the location of each card in the play area** is always open information.

A small wording change to make it clearer what is implied by the rule: The "where" of a card is a *location*, in the game technical sense. Physical location on the table is not pertinent here.

#### 8.5.6a, b - REVISED
> **[CR 22.12](/cr/22.12-Annotated.html#pf4f)**  
> a. When installing an agenda or asset in the root of a remote server, or an upgrade in the root of any server, the Corp may first trash any **number of** other cards already installed in the root of that server. If the card to be installed is an asset or agenda, the Corp must trash any other asset or agenda from that server. If the card to be installed is a region, the Corp must trash any other region from that server.
>
> b. When installing ice protecting a server, the Corp may first trash any **number of** other ice already installed protecting that server. Ice trashed in this way will not be counted when determining the install cost of the new ice.

A slight rewording to make it slightly more clear exactly which cards can be trashed.

#### 8.5.14 - ADDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf51)**  
> **Some abilities install cards to a specific location. If an ability specifies a destination that is invalid or cannot be identified, no installation can take place.**

With the addition to the game of new abilities capable of firing ice subroutines on ice that are not currently installed, this rule ensures the behavior when such subroutines reference locations relative to the (assumed) installed position of that ice is well-defined. Any references like "directly inward" (as seen on Brân 1.0) are invalid in these situations, and abilities that try to use them will have no effect.

The rule formerly known as 8.5.14, "Steps of Installing a Card" is now rule 8.5.15.

#### 8.8.4d - EXPANDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf55)**  
> **d. If a card is swapped with a set-aside card, the card moving into the set-aside zone becomes part of the group of cards being acted on by the ability that had set the other card aside, and the card moving out of the set-aside zone ceases to be acted on by that ability. See rule 8.4.3b for a specific case where this can happen, and see also rule 4.8.3 regarding effects acting on cards in the set-aside zone.**

This addition to the swapping rules is a complement to the Daily Business Show related changes, which makes it clear exactly how the state of swapped cards change when moving in and out of the set-aside zone.

#### 9.1.3b - REVISED
> **[CR 22.12](/cr/22.12-Annotated.html#pf55)**  
> b. If something grants an ability to an object **(see section 9.1.9)**, the source of the granted ability is that object, not whatever granted the ability.

Merely added a reference to the new 9.1.9 rule.

#### 9.1.9a,b,c - ADDED
> **[CR 22.12](/cr/22.12-Annotated.html#pf55)**  
> **Static abilities and lingering effects can make objects gain or lose abilities.**
>
> **a. If an object loses an ability, that ability is completely ignored. If the lost ability is a subroutine, it is not considered by any effect that counts subroutines on that object.**
>
> **b. To determine the actual abilities present on an object (as well as its other characteristics), follow the procedure described in rule 9.12.1d and rule 9.12.1e.**
>
> **c. Abilities on an object have no particular order, except for play abilities and subroutines. Play abilities cannot be added to or removed from an event or operation, and their order is the order they appear on their source card. To determine the order of subroutines on an object, refer to section 9.8.2 and section 9.8.3.**

This new rule declares the existence of abilities that add or remove abilities from other objects (like Hush, but there are also older examples, such as [Employee Strike](https://netrunnerdb.com/en/card/09053)). It does not appear to have any direct gameplay implications of its own, but contains several references to other rules which contain text that do affect game behavior.

#### 9.8.5a - REWORDED
> **[CR 1.6](/cr/1.6.html#pf66)**  
> a. When an encounter begins, each of **its** subroutines becomes unbroken with respect to that encounter.

> **[CR 22.12](/cr/22.12-Annotated.html#pf68)**  
> a. When an encounter begins, each of **the encountered ice’s** subroutines becomes unbroken with respect to that encounter.

A simple grammar update.

### References
This article uses the [NSG Comprehensive Rules Document version 22.12](https://nullsignal.games/wp-content/uploads/2022/12/Null-Signal-Games-Netrunner-Comprehensive-Rules-v22.12.pdf), which was released on 9 December 2022.

For convenience of linking, this article also uses hosted versions of [CR 1.6](http://localhost:4000/cr/1.6.html) and [CR 22.12](http://localhost:4000/cr/22.12-Annotated.html) (the annotated version with changes highlighted - page counts and references differ slightly between this and the standard version). These are identical to the PDF documents found on the NSG site, but I can't guarantee that my own hosted materials are always up to date, so when in doubt, always refer to the official versions. The page numbers below refer to the non-annotated document.

**Rules mentioned:**  
*Chapter 1: Game Concepts*  
1.21.2a (p.28)  
1.8.4 (p.10)  
1.8.4a (p.11)  
1.8.4b (p.11)

*Chapter 3: Card Types*  
3.6.5 (p.37)

*Chapter 4: Game Zones*  
4.2.3a (p.42)  
4.6.2 (p.45)  
4.6.6g (p.47)  
4.6.6i (p.47)  
4.6.6j (p.47)  
4.8.3 (p.50)  
4.8.7 (p.50)

*Chapter 8: Card Manipulation*  
8.1.4a (p.75)  
8.1.4b (p.75)  
8.4.3b (p.78)  
8.5.6a (p.79)  
8.5.6b (p.79)  
8.5.14 (p.81)  
8.5.15 (p.81)  
8.7.3 (p.84)  
8.8.4c (p.85)  
8.8.4d (p.85)  

*Chapter 9: Abilities*  
9.1.3b (p.86)  
9.1.8b (p.87)  
9.1.8g (p.88)  
9.1.9 (p.88)  
9.1.9a (p.89)  
9.1.9b (p.89)  
9.1.9c (p.89)  
9.6.2 (p.98)  
9.8.2 (p.103)  
9.8.2b (p.103)  
9.8.3 (p.104)  
9.8.5a (p.104)  
9.8.10 (p.106)  
9.8.11 (p.106)

*Chapter 10: Additional Rules*  
10.1.5 (p.121)

**Cards mentioned:**  
[Hush](https://netrunnerdb.com/en/card/33071)  
[Magnet](https://netrunnerdb.com/en/card/10103)  
[Nanisivik Grid](https://netrunnerdb.com/en/card/33111)  
[ZATO City Grid](https://netrunnerdb.com/en/card/33127)  
[Daily Business Show](https://netrunnerdb.com/en/card/06086)  
[Blueberry Diesel](https://netrunnerdb.com/en/card/26012)  
[The Class Act](https://netrunnerdb.com/en/card/26018)  
[Nanuq](https://netrunnerdb.com/en/card/33088)  
[Tsakhia "Bankhar" Gantulga](https://netrunnerdb.com/en/card/33074)  
[Persephone](https://netrunnerdb.com/en/card/12042)  
[Chief Slee](https://netrunnerdb.com/en/card/11077)  
[Media Blitz](https://netrunnerdb.com/en/card/09021)  
[Konjin](https://netrunnerdb.com/en/card/26109)  
[Surveyor](https://netrunnerdb.com/en/card/21118)  
[Colossus](https://netrunnerdb.com/en/card/13048)  
[Warroid Tracker](https://netrunnerdb.com/en/card/12068)  
[Daily Business Show](https://netrunnerdb.com/en/card/06086)  
[Blueberry Diesel](https://netrunnerdb.com/en/card/26012)  
[The Class Act](https://netrunnerdb.com/en/card/26018)  
[Warden Fatuma](https://netrunnerdb.com/en/card/21093)  
[Mother Goddess](https://netrunnerdb.com/en/card/06010)  
[Ansel 1.0](https://netrunnerdb.com/en/card/30038)  
[Private Security Force](https://netrunnerdb.com/en/card/01107)  
[Turntable](https://netrunnerdb.com/en/card/08043)  
[Exchange of Information](https://netrunnerdb.com/en/card/10092)  
[EMP Device](https://netrunnerdb.com/en/card/10020)  
[Dr. Lovegood](https://netrunnerdb.com/en/card/09042)  
[Imp](https://netrunnerdb.com/en/card/02003)  
[Stargate](https://netrunnerdb.com/en/card/26004)  
[Spin Doctor](https://netrunnerdb.com/en/card/30053)
[Muertos Gang Member](https://netrunnerdb.com/en/card/08068)  
[DJ Fenris](https://netrunnerdb.com/en/card/22025)  
[Wetwork Refit](https://netrunnerdb.com/en/card/11071)  
[Security Testing](https://netrunnerdb.com/en/card/05048)  
[Net-Ready Eyes](https://netrunnerdb.com/en/card/08047)  
[Matryoshka](https://netrunnerdb.com/en/card/33094)  
[Street Peddler](https://netrunnerdb.com/en/card/08062)  
[Bookmark](https://netrunnerdb.com/en/card/08106)  
[Free Lunch](https://netrunnerdb.com/en/card/12035)  
[Rover Algorithm](https://netrunnerdb.com/en/card/12100)  
[Employee Strike](https://netrunnerdb.com/en/card/09053)  

**Other:**  
[NSG Comprehensive Rules Document version 1.5](https://nisei.net/wp-content/uploads/2021/10/NISEI-Comprehensive-Rules-v1.5-clean.pdf)  
[NSG Comprehensive Rules Document version 1.6](https://nisei.net/wp-content/uploads/2022/07/NISEI-Comprehensive-Rules-v1.6-Clean.pdf)  
[NSG Card Text Updates Document version 22.12](https://nullsignal.games/wp-content/uploads/2022/12/Null-Signal-Games-Netrunner-Card-Text-Updates-v22.12.pdf)

### Acknowledgements
*Huge thanks to*  
Jamie Perconti, NSG rules manager, for answering lots of pedantic questions.  
Cephalopod Wizard, NSG rules team, for answering slightly fewer - but equally detailed - questions.

*Proofreading & factchecking*  
Vigeous

### Footnotes
[^1]: Probably not.

[^2]:  ***CR 1.21.2a*** *A player may look at facedown cards they control at any time.*

[^3]: Why though?