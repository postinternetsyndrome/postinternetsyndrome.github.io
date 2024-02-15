---
layout: post
title:  "Ashes remastered rules preview"
date:   2024-02-15 12:00:00
categories: news
tags: [news, spoilers, interviews]
image:
  feature: /ashes-remastered/mirrormorph.jpg
  credit: Null Signal Games/Olie Boldador
  creditlink: https://www.artstation.com/olieart
---

*Same, but different.*

The release of the remastered edition of the Ashes cycle will imminently be upon us, and I have been invited by NSG to show off some of the geekier details of this project. As most of you probably know, the Ashes remaster is in principle just a clean-up operation. New card backs, adjusting the alignment of some of the artwork, updating the card text to the latest official version. However, what's not been fully revealed until now is that those card text changes are not just whatever's on nrdb right now, but fresh out of the lab. Alongside them are also a few updates to the CR which, while still rather niche, should probably excite rules dorks from across Netrunnerdom.

A non-exhaustive selection of the card text updates will be given below. Many minor changes have been made which I have chosen not to include here. Those interested in a complete catalog of changes will have to peruse the official Card Text Updates document when it arrives.

Also joining me is NSG rules team manager Jamie Perconti, who has been very helpful about answering very very detailed questions about very very unimportant things. Most of Jamie's contributions can be found in the [Individual card changes](#individual-card-changes) section.

### Contents
- [Rules changes](#rules-changes)
  - [Second-degree NCIGS](#second-degree-ncigs)
  - [Objection!](#objection)
- [Individual card changes](#individual-card-changes)
  - [Always Have a Backup Plan](#always-have-a-backup-plan)
  - [The Class Act](#the-class-act)
  - [Whistleblower](#whistleblower)
  - [Red Level Clearance](#red-level-clearance)
  - [Game Over](#game-over)
  - [Vulnerability Audit](#vulnerability-audit)
  - [Hoshiko Shiro](#hoshiko-shiro)
  - [Harmony AR Therapy](#harmony-ar-therapy)
  - [Simulchip](#simulchip)
  - [Engram Flush](#engram-flush)
  - [Hyoubu Precog Manifold](#hyoubu-precog-manifold)
  - [La Costa Grid](#la-costa-grid)
  - [SYNC Rerouting](#sync-rerouting)
  - [Transport Monopoly](#transport-monopoly)
  - [Wall to Wall](#wall-to-wall)
  - [Winchester](#winchester)
- [General card changes](#general-card-changes)
  - [Numeral quantities](#numeral-quantities)
  - [Companions](#companions)
  - [Condition before effect](#condition-before-effect)
  - [Turn ends -> discard phase ends](#turn-ends---discard-phase-ends)
  - [X](#x)
  - [Set aside](#set-aside)
  - [Has -> gets](#has---gets)
  - [Psi Game](#psi-game)
  - [Tokens and counters](#tokens-and-counters)
  - [Effect ordering](#effect-ordering)
  - [Quoted abilities](#quoted-abilities)
  - ["You can spend"](#you-can-spend)
- [Other notes](#other-notes)

  
# Rules changes
The exact CR text is not yet published, but I have had the opportunity to speak to rules team manager Jamie Perconti about the upcoming changes, so what you'll get here is an informal explanation of what the new rules will entail, which may well differ in their exact implementation compared to the full CR update which will arrive at a later date.

## Second-degree NCIGS
The first one isn't even formally a rules change, but rather a change in the official *interpretation* of the current rules text. As I touched upon in my [old article](/essays/cost-and-effect/#appendix-b-not-created-equal) about the "no change in game state" (NCIGS) rule, the way NCIGS interacts with operations and events is a bit fuzzy. The rules state that only the effect of an ability is considered when evaluating NCIGS, but this gets convoluted when we're talking about the basic ability to play an operation or event. In those cases, the accepted norm has been that you then *also* recursively evaluate NCIGS for the event/operation card itself, checking whether the effect of the event or operation has the potential to change the game state. This is why you - up until now - couldn't play [Diesel](https://netrunnerdb.com/en/card/31027) with an empty stack, and similar.

This is about to change. As a - and I quote - "first stage of NCIGS reform", this interpretation is being discarded. From now on, this secondary NCIGS evaluation when playing operations and events is no longer necessary. You will need only to be able to pay the cost of the card in order to perform the basic action to play an operation or event. Play Diesel just to get it out of your hand? Absolutely fine. Play [Legwork](https://netrunnerdb.com/en/card/31019) after an [Excalibur](https://netrunnerdb.com/en/card/29017) fire to dodge [Economic Warfare](https://netrunnerdb.com/en/card/21036)? Go right ahead.

This solves the age-old issue with the original wording of [Scavenge](https://netrunnerdb.com/en/card/03034), where you had to have a valid target in the heap in order to play it, even if resolving the cost would obviously create such a target. Because of this, Scavenge will be returned to its original wording in the future, and [Rejig](https://netrunnerdb.com/en/card/26029) is receiving a similar change right away:

> **Add an installed program or piece of hardware to your grip. If you do, you may** install **a** program or piece of hardware, paying X[credit] less. X is equal to the printed install cost of the **uninstalled card**.

> **As an additional cost to play this event, add 1 installed program or piece of hardware to your grip.**  
> Install **1** program or piece of hardware **from your grip**, paying X[credit] less. X is equal to the printed install cost of the **card you added to your grip**.

[![Rejig](https://card-images.netrunnerdb.com/v1/large/26029.jpg)](https://netrunnerdb.com/en/card/26029)
![Rejig](/images/ashes-remastered/ASH_DFL_29 (Small).png)

Perhaps disappointing to NCIGS enthusiasts, [Simulchip](https://netrunnerdb.com/en/card/26085) - which has a very similar additional cost - will not be affected by this round of changes and continues to require a pre-existing target to trigger. The same goes for [Reconstruction Contract](https://netrunnerdb.com/en/card/21020). Only operations and events will change as a result of this reinterpretation, not other types of abilities.

These are exciting times though, since this not only makes the rules simpler to explain, but also bears the promise of more to come. A lot of us have been eagerly awaiting the eventual banishment of NCIGS into the void, and it seems as if actual movement towards that goal has now begun.

## Objection!
The second change *does* affect the CR directly. In the still to this day controversial CR 1.5 - which introduced a lot of major changes - NSG significantly revised the access rules. The intention was to simplify the access procedure and make it much clearer how cards like [Bacterial Programming](https://netrunnerdb.com/en/card/21033) affect an ongoing breach of archives. This objective was achieved, but it had the side effect of creating one of the most infamous combos of modern Netrunner:

<iframe width="420" height="315" src="/videos/ganked.mp4" frameborder="0" allowfullscreen></iframe>

The [Ganked!](https://netrunnerdb.com/en/card/26119) + [Ansel](https://netrunnerdb.com/en/card/30038) [infinite loop](/videos/ganked.mp4) was born.

Some people think that this might have been unintended, but when no changes were made to these rules in the several CR versions following 1.5, players eventually began to accept that this was just how Netrunner worked now. Whether you approved or not, the Ganked! loop was here to stay, it seemed.

However! The rules team have finally changed their mind. In the new CR, the access rules will have a new provision written into them: When a card becomes installed in the root of a server while cards in that server are being accessed, the runner can *choose* to make that card an access candidate (in the next checkpoint following the install). But they are not *forced* to do so. This means that when the corp reinstalls Ganked!, the runner may simply elect not to access it again, completely turning off the loop compo we've all learned to love/hate.

[![Ganked!](/images/ashes-remastered/ASH_UPR_119 (Small).png)](https://netrunnerdb.com/en/card/26119)
[![Ansel 1.0](https://card-images.netrunnerdb.com/v1/large/30038.jpg)](https://netrunnerdb.com/en/card/30038)

There's still some room for shenanigans though. If the new card is installed from a facedown location, the runner will have to make the decision whether to access it or not blindly. Is it a trap to avoid or a defensive upgrade that you'll want to trash? Choose wisely. But the risk of complete blow-out situations where the runner gets completely board wiped is significantly reduced.

# Individual card changes
What follows is a list of cards with bespoke changes, although some of them are representative of trends we have already seen and will be seeing more of in the future.

## Always Have a Backup Plan
[This card](https://netrunnerdb.com/en/card/26011) has been changed make it clearer that the second run is made against the server which was the attacked server when the first run ended, regardless of where it started. This was already codified in a ruling from the [Downfall Release Notes](https://nullsignal.games/products/Downfall/DFReleaseNotes/#QandAforDownfall), but this reading should now be a bit more intuitive to make.

> **CTU 22.12**  
> Run any server. When that run ends, if it was unsuccessful, you may run **that** server again, ignoring any additional costs to run. During the second run, **when** you encounter the last ice you encountered in the first run, bypass it.

> **Ashes Remastered**  
> Run any server. When that run ends, if it was unsuccessful, you may run **the attacked** server again, ignoring any additional costs to run. During the second run, **whenever** you encounter the last piece of ice you encountered during the first run, bypass it.

## The Class Act
No card text update is complete without a revision of [The Class Act](https://netrunnerdb.com/en/card/26018)! The original wording of this card allowed you to draw 4 cards on either player's turn, if the card was installed on it. At some point during the storied history of this card, that nuance got lost and it got locked into only triggering on the runner's turn. This has probably not been noticed by many people, since you need special tools like [DaVinci](https://netrunnerdb.com/en/card/08107) to install resources on the corp's turn. But, as Jamie says: 

> **Jamie**  
> Once it was pointed out that we had inadvertently changed the first ability too, well, we had to fix it.

> **CTU 22.12**  
> When **your** discard phase ends, if you installed this resource this turn, draw 4 cards.  
> [interrupt] → The first time each turn you would draw any number of cards, look at the top X cards of your stack. Add 1 of those cards to the bottom of your stack. X is equal to the number of cards you **will** draw plus 1.

> **Ashes Remastered**  
> When **a** discard phase ends, if you installed this resource this turn, draw 4 cards.  
> [interrupt] → The first time each turn you would draw any number of cards, look at the top X cards of your stack. Add 1 of those cards to the bottom of your stack. X is equal to the number of cards you **would** draw plus 1.

## Whistleblower
A pure style change. The rules team prefers to use more neutral terms (like "card") unless more specificity is required. If you absolutely don't want [Whistleblower](https://netrunnerdb.com/en/card/26030) to trigger for some reason during a run against [Ampére](https://netrunnerdb.com/en/card/33128) (but you *do* want to trash Whistleblower), you can now name a non-agenda card and guarantee it, but the utility of such a play is severely limited. (Against any other corp, of course, you could already name an agenda from another faction and be safe.)

> **CTU 22.12**  
> Whenever you make a successful run, you may trash this resource to name **an agenda**. The next time this run you access **a copy of the named agenda**, steal it, ignoring all costs. (You are no longer accessing it.)

> **Ashes Remastered**  
> Whenever you make a successful run, you may trash this resource to choose **a card name**. The next time this run you access **an agenda with the chosen name**, steal it, ignoring all costs. (You are no longer accessing it.)

## Red Level Clearance
It was never clear why [Red Level Clearance](https://netrunnerdb.com/en/card/26037) should say "install up to 1 non-agenda card" and now it doesn't anymore.

> **CTU 22.12**  
> Resolve two of the following in any order:
> - Draw 2 cards.
> - Gain 2[credit].
> - Install **up to** 1 non-agenda card.
> - Gain [click].

> **Ashes Remastered**  
> Resolve 2 of the following in any order:
> - Draw 2 cards.
> - Gain 2[credit].
> - Install 1 non-agenda card **from HQ**.
> - Gain [click].

## Game Over
While still not using the interrupt glyph (which doesn't fit naturally into card text in all situations), the implicit interrupt ability on [Game Over](https://netrunnerdb.com/en/card/26053) has been made more clear by the use of the word "would".

> **CTU 22.12**  
> Play only if the Runner stole an agenda during their last turn.  
> Choose a Runner card type. Trash all installed non-icebreaker cards of **that** type. **The Runner may prevent any of those cards from being trashed by paying 3[credit] each.** Take 1 bad publicity.

> **Ashes Remastered**  
> Play only if the Runner stole an agenda during their last turn.  
> Choose a Runner card type. Trash all installed non-icebreaker cards of **the chosen** type. **For each card that would be trashed this way, the Runner may pay 3[credit] to prevent that card from being trashed.**  
> Take 1 bad publicity.

## Vulnerability Audit
In principle, the old text on [Vulnerability Audit](https://netrunnerdb.com/en/card/26063) allowed you to score it on the same turn as it was installed, *if it was installed by the runner*. That seems unlikely to ever occur, but the rules team are dotting their i's and crossing their t's on this one.

> **Jamie**  
> We don’t see the text tweak to Vulnerability Audit as a functional change. Players shouldn’t ever be installing each other’s cards. Not only is there weirdness here with the built-in cost payment that’s part of an install, but the possibility of trashing your opponent’s other cards makes this hypothetical effect severely problematic.

> **CTU 22.12**  
> You cannot score this agenda if **you installed it** this turn.

> **Ashes Remastered**  
> You cannot score this agenda if **it was installed** this turn.

## Hoshiko Shiro
In a rare move, [Hoshiko](https://netrunnerdb.com/en/card/26066) is getting changed to using text instead of numerals, which is counter to the general direction the NSG rules team is moving in.

> **Jamie**  
> We prefer to use numerals when the specific number is important, particularly when we’re writing an instruction. In other contexts, like this one, the question being asked is more about “did this happen at all” than “did this happen a specific number of times.”
>
> For Hoshiko in particular, we felt the need to include the extra emphasis of “at least 1” in the original printing, because at the time “accessed a card” meant something totally different from the very similar-looking “accessed cards”. The “breach” terminology we introduced with System Gateway was specifically intended to remove this unintuitive terminology overlap, and it’s been around long enough now that we are comfortable with a more natural phrasing for Hoshiko.

Additionally, while NSG are generally moving towards consistency and uniformity as much as possible, the flip side of this card is being changed to a different wording than the front.

> **Jamie**  
> We try to avoid ambiguity where we can, even those where the incorrect reading doesn’t hold up to scrutiny. The condition “if you did not access a card this turn” has the potential to be misread as “if there is a card you did not access this turn,” whereas “if you did not access any cards this turn” can’t plausibly be parsed that way.

> **CTU 22.12**  
> When your turn ends, if you accessed **at least 1** card this turn, gain 2[credit] and flip this identity.  
> [Flip side]:   
> When your turn begins, draw 1 card and lose 1[credit].  
> When your turn ends, if you did not access **at least 1 card** this turn, flip this identity.

> **Ashes Remastered**  
> When your turn ends, if you accessed **a** card this turn, gain 2[credit] and flip this identity.  
> [Flip side]:  
> When your turn begins, draw 1 card and lose 1[credit].  
> When your turn ends, if you did not access **any cards** this turn, flip this identity.

[![Hoshiko Shiro](https://card-images.netrunnerdb.com/v1/large/26066.jpg)](https://netrunnerdb.com/en/card/26066)
![Hoshiko Shiro](/images/ashes-remastered/ASH_UPR_66.1 (Small).png)

[![Hoshiko Shiro](/images/ashes-remastered/26066flip.png)](https://netrunnerdb.com/en/card/26066)
![Hoshiko Shiro](/images/ashes-remastered/ASH_UPR_66.2 (Small).png)

## Harmony AR Therapy
[Harmony AR Therapy](https://netrunnerdb.com/en/card/26083) no longer "searches" the heap for 5 cards, you now merely "choose" them. While searching other zones than R&D or the Stack is [not unprecedented](https://netrunnerdb.com/en/card/31028), it is rare and there's nothing about this card that requires the rules framework that comes along with "searching" specifically.

> **CTU 22.12**  
> **Search your heap for** up to 5 cards with different names. Shuffle those cards into your stack. **Remove this card from the game instead of trashing it.**

> **Ashes Remastered**  
> **Choose** up to 5 cards with different names **in your heap**. Shuffle those cards into your stack.  
> **Remove this event from the game.**

[![Harmony AR Therapy](https://card-images.netrunnerdb.com/v1/large/26083.jpg)](https://netrunnerdb.com/en/card/26083)
![Harmony AR Therapy](/images/ashes-remastered/ASH_UPR_18 (Small).png)

## Simulchip
In further reordering news, the static ability on Simulchip now has the term "additional cost" earlier in the sentence, to give the reader an easier time to pick up on what type of effect this is at a glance.

> **CTU 22.12**  
> **If no installed programs have been trashed this turn, you must trash 1 installed program as an additional cost to use this hardware.**  
> \[trash]: Install 1 program from your heap, paying 3[credit] less.

> **Ashes Remastered**  
> **As an additional cost to use this hardware, trash 1 installed program. Ignore this cost if an installed program has already been trashed this turn.**  
> \[trash]: Install 1 program from your heap, paying 3[credit] less.

## Engram Flush
Just some minor terminology changes here to bring [Engram Flush](https://netrunnerdb.com/en/card/26108) in line with modern standards. I was a bit mystified though, by the change to "the encounter" from "this encounter", when the latter appears to be a more commond wording overall, including being used in recent NSG releases. Jamie's answer was more detailed than I expected!

> **Jamie**  
> We’ve thought a lot about “the” versus “that” versus “this” over the years, and in many cases there is a lot of nuance to how we choose which of those words we use. But I have to admit this question surprised me. The original printing of Engram Flush used “the encounter”, and it looks like we changed it to “this encounter” in a Card Text Updates release in 2021… but I’m not sure why we did that. Our style requires the use of “this encounter” when there has been no previous mention of the encounter in question, but it’s less clear about cases like this where “When the Runner encounters this ice” appears earlier in the ability.

> **CTU 22.12**  
> When the Runner encounters this ice, choose a card type. For the remainder of **this** encounter, whenever you reveal the grip with a subroutine on this ice, you may trash 1 revealed card of **that** type.  
> [subroutine] Reveal the grip.  
> [subroutine] Reveal the grip.

> **Ashes Remastered**  
> When the Runner encounters this ice, choose a card type. For the remainder of **the** encounter, whenever you reveal the grip with a subroutine on this ice, you may trash 1 revealed card of **the chosen** type.  
> [subroutine] Reveal the grip.  
> [subroutine] Reveal the grip.

## Hyoubu Precog Manifold
This card has received an extremely minor change, but a lot of thinking went into it.

> **Jamie**  
> [Hyoubu Precog Manifold](https://netrunnerdb.com/en/card/26110)’s original printing has a pretty strange wording quirk. “Play abilities” are the abilities on an event or operation that resolve when you play the card. But events and operations can also have any of the other types of abilities, particularly lockdowns and currents, which in some ways have more in common with installable cards than with other events and operations, because the whole point of those subtypes is that the card remains active for a period of time. Lockdowns and currents mostly tend to have static abilities and conditional abilities, and only very few have any play abilities at all.
>
> The quirk of Hyoubu Precog Manifold is that, despite it having a pretty packed text box, the instructions you resolve at the time you play the operation, in their entirety, are: “Choose a server.”
>
> Weird, right? Everything else on the card is a static ability restricting how the card is played or trashed, or a conditional ability that hangs around waiting for a run. Buried amidst all that, we felt that the one “Choose a server.” instruction could be better contextualized by writing its timing explicitly. This also allows it to mirror “when installed” abilities on other cards. Technically, the new wording moves the choice of server from step [8.6.6f](https://rules.nullsignal.games/?r=rule_steps_playing_resolve_play_abilities) to step [8.6.6e](https://rules.nullsignal.games/?r=rule_steps_playing_played_checkpoint), but that doesn’t have any practical functional implications.

> **CTU 22.12**  
> Play only if there is no active lockdown. This operation is not trashed until your next turn begins.  
> Choose a server.  
> Whenever the Runner makes a successful run on the chosen server, **you and the Runner secretly spend 0[credit], 1[credit], or 2[credit]. Reveal spent credits. If you and the Runner spent a different number of credits**, end the run.

> **Ashes Remastered**  
> Play only if there is no active lockdown. This operation is not trashed until your next turn begins.  
> **When you play this operation,** choose a server.  
> Whenever the Runner makes a successful run on the chosen server, **play a Psi Game. (Players secretly bid 0–2[credit]. Then each player reveals and spends their bid.) If the bids differ**, end the run.

[![Hyoubu Precog Manifold](https://card-images.netrunnerdb.com/v1/large/26110.jpg)](https://netrunnerdb.com/en/card/26110)
![Hyoubu Precog Manifold](/images/ashes-remastered/ASH_UPR_45 (Small).png)

## La Costa Grid
[La Costa Grid](https://netrunnerdb.com/en/card/27005) now specifies that the target card must be installed.

> **Jamie**  
> We don’t consider this a functional change. There’s no way to have a non-installed card in the root of a server, and there are enough questions about what that would even mean that we don’t expect to see that change any time soon.

> **CTU 22.12**  
> Remote server only.  
> When your turn begins, place 1 advancement counter on a card **installed** in the root of this server.  
> Limit 1 region per server.

> **Ashes Remastered**  
> Remote server only.  
> When your turn begins, place 1 advancement counter on a card in the root of this server.  
> Limit 1 region per server.

## SYNC Rerouting
The tag ability on [SYNC Rerouting](https://netrunnerdb.com/en/card/26118) is being changed to use a nested cost.

> **Jamie**  
> We’re generally moving away from the “must X or Y” construction when we can. It has a bunch of nuances that we don’t want players to have to memorize, and frequently a nested cost can do the job. That said, we don’t want to change the behavior of existing cards that use the construction, so we don’t put effects that can be prevented into cost positions. For example, [Data Raven](https://netrunnerdb.com/en/card/25112) says the Runner “must take 1 tag or end the run.”. If we changed it to use [Funhouse](https://netrunnerdb.com/en/card/30054)’s “...end the run unless the Runner takes 1 tag.”, it would no longer interact the same way with effects that avoid tags. If we instead changed Data Raven to “...give the Runner 1 tag unless they end the run.”, it would no longer interact the same way with [Lucky Charm](https://netrunnerdb.com/en/card/26014).
>
> SYNC Rerouting is a case where we can safely switch to a nested cost. There are no interrupts that modify “Pay 4[credit].”, so putting it into a cost position is not a functional change. Fairchild 3.0 is the same, and we will probably end up making a similar change there eventually, but since the card is no longer in Standard, it’s pretty low among our Card Text Updates priorities.

> **CTU 22.12**  
> Play only if there is no active lockdown. This operation is not trashed until your next turn begins.  
> Whenever a run begins, **the Runner must pay 4[credit] or take 1 tag**.

> **Ashes Remastered**  
> Play only if there is no active lockdown. This operation is not trashed until your next turn begins.  
> Whenever a run begins, **give the Runner 1 tag unless they pay 4[credit]**.

## Transport Monopoly
> **Jamie**  
> You already couldn’t use [Transport Monopoly](https://netrunnerdb.com/en/card/26121)’s ability outside of a run, because it doesn’t pass the “potential to change the game state” check. But we added the explicit restriction so that the phrase “this run” is well-defined.

> **CTU 22.12**  
> When you score this agenda, place 2 agenda counters on it.
> Hosted agenda counter: This run cannot be declared successful. (This effect does not cause the run to become unsuccessful.) Use this ability only once per turn.

> **Ashes Remastered**  
> When you score this agenda, place 2 agenda counters on it.
> Hosted agenda counter: This run cannot be declared successful. (This effect does not cause the run to become unsuccessful.) Use this ability only once per turn **and only during a run**.

## Wall to Wall
[Wall to Wall](https://netrunnerdb.com/en/card/26122) has been updated for consistency with all other modular cards, which already used the "in any order" wording.

> **CTU 22.12**  
> When your turn begins, if you have any other rezzed assets, resolve 1 of the following; otherwise, resolve up to 3:
> - Draw 1 card.
> - Gain 1[credit].
> - Place 1 advancement token on **a** piece of ice.
> - Add this asset to HQ.

> **Ashes Remastered**  
> When your turn begins, if you have any other rezzed assets, resolve 1 of the following; otherwise, resolve up to 3 **in any order**:
> - Draw 1 card.
> - Gain 1[credit].
> - Place 1 advancement counter on **an installed** piece of ice.
> - Add this asset to HQ.

## Winchester
In an unusual move, the ability granting [Winchester](https://netrunnerdb.com/en/card/26125) an extra subroutine has been moved to after the printed subroutines on the card. This is now the one ice in the game with ability text after the subroutines. Even other cards which add subroutines after the existing subs - like [Starlit Knight](https://netrunnerdb.com/en/card/34053) - tend to have the ability doing so at the top of the text box. Jamie explains why this card is a special case.

> **Jamie**  
> It’s a spatial reasoning thing, yes. I personally have often found Winchester confusing in play, because its subroutines are complex (all different from each other, and all involving traces) and appear on the card in a different order than they resolve, and I’ve anecdotally found that a lot of players agree with me on that. So this change is attempting to improve that situation. Cards like Starlit Knight that just add a bunch of copies of a straightforward “[subroutine] End the run.” subroutine don’t particularly need this special treatment.

> **CTU 22.12**  
> **While this ice is protecting HQ, it gains "[subroutine] Trace[3]. If successful, end the run." after all its other subroutines.**  
> [subroutine] Trace[4]. If successful, trash 1 installed program.  
> [subroutine] Trace[3]. If successful, trash 1 installed piece of hardware.

> **Ashes Remastered**  
> [subroutine] Trace[4]. If successful, trash 1 installed program.  
> [subroutine] Trace[3]. If successful, trash 1 installed piece of hardware.  
> **While this ice is protecting HQ, it gains "[subroutine] Trace[3]. If successful, end the run." after its other subroutines.**

[![Winchester](https://card-images.netrunnerdb.com/v1/large/26125.jpg)](https://netrunnerdb.com/en/card/26125)
![Winchester](/images/ashes-remastered/ASH_UPR_125 (Small).png)

# General card changes
In this section I have lumped together cards in groups which have received similar changes. Most of the changes are minor, but serve to illustrate the direction the game is moving in with regards to how cards are written.

## Numeral quantities
We have already seen a number of changes like this in earlier card text updates. NSG these days tries to refer to quantities using numerals rather than words. Several cards have had instances of words like "a" or "an" changed to numbers instead.

Isolation  
Spec Work  
SDS Drone Deployment  
The Artist  
Red Level Clearance  
Secure And Protect  
Boomerang  
Cordyceps  
Self-modifying Code

[![Self-modifying Code](https://card-images.netrunnerdb.com/v1/large/26090.jpg)](https://netrunnerdb.com/en/card/26090)
![Self-modifying Code](/images/ashes-remastered/ASH_UPR_25 (Small).png)

## Companions
The companions have been reworded to say "when your turn begins **and whenever** you steal an agenda" instead of "when your turn begins **or** you steal an agenda".

Fencer Funeno  
Trickster Taka  
Mystic Maemi  
Paladin Poemu

[![Paladin Poemu](https://card-images.netrunnerdb.com/v1/large/26073.jpg)](https://netrunnerdb.com/en/card/26073)
![Paladin Poemu](/images/ashes-remastered/ASH_UPR_8 (Small).png)

## Condition before effect
A consistency principle that NSG has started to apply is that conditions are placed before other content in ability text. These changes are usually just a matter of moving some words around on the card, but the idea is to describe the condition in full before moving on to the effects, avoiding sentences like "when X, do Y if Z" where the effect is sandwiched beetween different fragments of the condition.

Daily Quest  
Prognostic Q-Loop  
Penumbral Toolkit  
Megaprix Qualifier

[![Megaprix Qualifier](https://card-images.netrunnerdb.com/v1/large/27004.jpg)](https://netrunnerdb.com/en/card/27004)
![Megaprix Qualifier](/images/ashes-remastered/ASH_UPR_31 (Small).png)

### Variants
A special case is ["Baklan" Bochkin](https://netrunnerdb.com/en/card/26017), which has the condition removed entirely from the ability text and integrated into the cost.

> **CTU 22.12**  
> The first time **each run** you encounter a piece of ice, place 1 power counter on this resource.  
> [trash]: Derez the ice you are encountering if its strength is **equal to or less than the number of hosted power counters**. Take 1 tag.

> **Ashes Remastered**  
> The first time you encounter a piece of ice **during each run**, place 1 power counter on this resource.  
> [trash]**, X hosted power counters**: Derez the ice you are encountering if its strength is **X or less**. Take 1 tag.

## Turn ends -> discard phase ends
[Lat](https://netrunnerdb.com/en/card/26019) is being changed to use the newer "discard phase ends" wording, which is functionally identical to "turn ends", but is used in some situations where it's considered relevant to emphasize that the player should discard before using the ability in question.

## X
NSG are continuing to expand their usage of the "X" construct, adding it here to two cards in lieu of "for each". "For each" is still used in a large number of places and is not being blanket replaced by X wordings.

Khusyuk  
Cerebral Overwriter

### Variants
[Focus Group](https://netrunnerdb.com/en/card/26052) already uses X, but has had its text reordered so the definition of X precedes the usage. The same change is not being generally applied to cards which use X, but was clearly considered more readable in this specific case.

Another special case is [The Back](https://netrunnerdb.com/en/card/26082), which is getting reworded to a more classical "for each" wording rather than an X-based one.

> **Jamie**  
> We have become more comfortable over time with frequent use of X for scaling effects, but The Back is a weird case because the scaling is doubled. We feel that “2 for each counter” is easier to grok than “2 times the number of counters”.

[![The Back](https://card-images.netrunnerdb.com/v1/large/26082.jpg)](https://netrunnerdb.com/en/card/26082)
![The Back](/images/ashes-remastered/ASH_UPR_17 (Small).png)

## Set aside
Khusyuk is being reworded to set aside cards rather than revealing them. Revealing cards from R&D is classically problematic, because if R&D changes during access you can get some really obtuse results. NSG are more and more preferring to set aside cards for this reason, which makes it clear that the cards being operated on are separate from R&D and will not be affected by changes to it.

> **CTU 22.12**  
> Run R&D. If successful, instead of breaching R&D, choose **a number** greater than 0. For each installed card you have with a printed install cost matching that number, reveal 1 card from the top of R&D (max 6). Access 1 of the **revealed** cards**, then the Corp shuffles R&D**.

> **Ashes Remastered**  
> Run R&D. If successful, instead of breaching R&D, choose **an install cost** greater than 0**[credit]**. The Corp sets aside the top X cards of R&D faceup, where X is equal to the number of your installed cards with that printed install cost, up to 6. Access 1 of the **set-aside** cards. **The Corp shuffles the set-aside cards into R&D.**

At the same time, [Gachapon](https://netrunnerdb.com/en/card/26069), the patient zero that taught us all that set aside cards are implicitly face up, is being changed to make that explicit in the card text as well.

[![Gachapon](https://card-images.netrunnerdb.com/v1/large/26069.jpg)](https://netrunnerdb.com/en/card/26069)
![Gachapon](/images/ashes-remastered/ASH_UPR_4 (Small).png)

> **CTU 22.12**  
> \[trash]: Set aside the top 6 cards of your stack. You may install 1 program or virtual resource from among **the set aside** cards, paying 2[credit] less. Shuffle 3 of the remaining cards into your stack, then remove the rest from the game.

> **Ashes Remastered**  
> \[trash]: Set aside the top 6 cards of your stack **faceup**. You may install 1 program or virtual resource from among **those** cards, paying 2[credit] less. Shuffle 3 of the remaining cards into your stack, then remove the rest from the game.

## Has -> gets
Several cards are getting the now standard rewording from "has" to "gets" for static modifications.

Supercorridor  
Hagen  
Sandstone  
Rime  
Akhet  
Colossus

## Psi Game
The three Psi cards in Ashes have received the expected rewording to use the new Psi Game keyword. All of them also have the Psi Game reminder text, which results in about the same volume of text as before on these cards.

> **Jamie**  
> Psi games are a mechanic with enough nuance that a set would have to be making pretty heavy use of it in order for us to consider omitting its reminder text from any of the cards. Reminder text lets us be a little less precise with language, which often saves text over writing out full rules. But even when it doesn’t reduce text length, the fact that it’s formatted in italics can make it easier for players who are already familiar with the mechanic to visually skip over the part they don’t need. And that in turn makes it easier to spot cards that break the trend of the mechanic, like [Aiki](https://netrunnerdb.com/en/card/11032)’s “reversed” Psi game[^1].

Letheia Nisei  
Konjin  
Hyoubu Precog Manifold

[![Letheia Nisei](https://card-images.netrunnerdb.com/v1/large/26046.jpg)](https://netrunnerdb.com/en/card/26046)
![Letheia Nisei](/images/ashes-remastered/ASH_DFL_46 (Small).png)

## Tokens and counters
Ever since System Gateway, NSG have gradually been replacing usages of the word "token" in rules and card text with the word "counter", which means the same thing. Jamie explains why they chose to keep the former over the latter:

> **Jamie**  
> While there are several counter types that used to be referred to as “tokens” in rules documents, “advancement tokens” are the only type that has ever been described that way in actual card text. So it was a pretty easy decision to go with “counter” and update one thing, rather than changing how we refer to power counters, virus counters, and so on.

Remastered Edition  
Focus Group  
Akhet  
Colossus  
NAPD Cordon

## Effect ordering
The ordering of certain effects is being moved around. I asked Jamie why.

> **Jamie**  
> We have several style rules for how to order things depending on the context. If an ability contains a list of subtypes, for example, we tend to put them in alphabetical order. With effects that give both cards and money, we tend to put the credit gain first so that it’s obvious that the player has the credits in their pool before they resolve “when you draw” abilities like Jinja City Grid.  
>
> For lists that are more complex and don’t have another particular pattern to follow, like the trigger conditions on Keiko or the modes on Bahia Bands, we tend to aim for a “logical” order. In other words, we write the list elements in the order that feels like the best match for when they will likely happen or when players will likely want to do them.  
>
> Link is not a huge part of the game right now, and “more important things first” is one of the principles we consider when ordering a list, just like the “logical order” we touched on before.

### Moshing
> **CTU 22.12**  
> As an additional cost to play this event, trash 3 cards from your grip.  
> **Draw 3 cards and gain 3[credit].**

> **Ashes Remastered**  
> As an additional cost to play this event, trash 3 cards from your grip.  
> **Gain 3[credit] and draw 3 cards.**

### Keiko
> **CTU 22.12**  
> +2[memory unit]  
> The first time each turn you **spend credits from or install a companion**, gain 1[credit].  
> Limit 1 console per player.

> **Ashes Remastered**  
> +2[memory unit]  
> The first time each turn you **install a companion card or spend credits from an installed companion card**, gain 1[credit].  
> Limit 1 console per player.

### Dreamnet
> The first time each turn you make a successful run, draw 1 card. **If you have at least 2[link] or your identity is digital**, also gain 1[credit].

> **Ashes Remastered**  
> The first time each turn you make a successful run, draw 1 card. **If your identity is digital or you have at least 2[link]**, also gain 1[credit].

### Next Activation Command
> **CTU 22.12**  
> Play only if there is no active lockdown. This operation is not trashed until your next turn begins.  
> **The Runner cannot use non-icebreaker cards to break subroutines. Each piece of ice has +2 strength.**

> **Ashes Remastered**  
> Play only if there is no active lockdown. This operation is not trashed until your next turn begins.  
> **Each piece of ice gets +2 strength.**  
> **The Runner cannot use non-icebreaker cards to break subroutines.**

[![Keiko](https://card-images.netrunnerdb.com/v1/large/26070.jpg)](https://netrunnerdb.com/en/card/26070)
![Keiko](/images/ashes-remastered/ASH_UPR_5 (Small).png)

## Quoted abilities
[Euler](https://netrunnerdb.com/en/card/26087) and [Penrose](https://netrunnerdb.com/en/card/26089) have received matching changes that replace the conditional ability granting them an extra ability with permanent abilities that are only usable if a condition is true. This makes the text more aesthetically pleasing, but that was not the main reason.

> **Jamie**  
> Lining up the interface flags is nice, but these cases were more about removing quoted abilities and creating consistency with the way [Utae](https://netrunnerdb.com/en/card/26005) and [Odore](https://netrunnerdb.com/en/card/26071) are written. Abilities granting quoted text to cards isn’t forbidden, but it’s one of the more difficult text patterns to follow, so nowadays we tend to avoid it when there’s a more-or-less equivalent way to write a card without it.

### Euler
> **CTU 22.12**  
> **When you install this program, for the remainder of the turn it gains "Interface → 0[credit]: Break 1 code gate subroutine."**  
> Interface → 2[credit]: Break up to 2 code gate subroutines.  
> 1[credit]: +1 strength.

> **Ashes Remastered**  
> **Interface → 0[credit]: Break 1 code gate subroutine. Use this ability only if this program was installed this turn.**  
> Interface → 2[credit]: Break up to 2 code gate subroutines.  
> 1[credit]: +1 strength.

### Penrose
> **CTU 22.12**  
> **When you install this program, for the remainder of the turn it gains "Interface → 1[credit]: Break 1 barrier subroutine."**  
> Interface → 1[credit]: Break 1 code gate subroutine.  
> 1[credit]: +3 strength. Use this ability only by spending a credit from a stealth card.

> **Ashes Remastered**  
> **Interface → 1[credit]: Break 1 barrier subroutine. Use this ability only if this program was installed this turn.**  
> Interface → 1[credit]: Break 1 code gate subroutine.  
> 1[credit]: +3 strength. Use this ability only by spending a credit from a stealth card.

[![Penrose](https://card-images.netrunnerdb.com/v1/large/26089.jpg)](https://netrunnerdb.com/en/card/26089)
![Penrose](/images/ashes-remastered/ASH_UPR_24 (Small).png)

## "You can spend"
Cards that host credits that can be used for various purposes are being migrated to the unified modern wording "you can spend" rather than obtuse phrases like "use these credits to XYZ".

Mystic Maemi  
Paladin Poemu  
Penumbral Toolkit  
Mantle  
Fencer Fueno  
Trickster Taka

# Other notes
While not part of the Ashes remaster project itself, I want to direct some extra attention towards the recently unveiled [https://rules.nullsignal.games/](https://rules.nullsignal.games/), which is the official version of the html rules I've used a prototype of in earlier articles. This resource has been online since at least January, but has not been publicly announced and is not linked from anywhere on the NSG site. It's a very convenient, searchable and linkable document, which also provides the linked rule as preview text on Discord and similar. I encourage all frequent readers of the CR to have a look!

The mobile version can still be improved, but is very useful regardless and I applaud this effort by NSG to make the CR more accessible and easy to use.

### References
This article uses the [NSG Comprehensive Rules Document version 23.08](https://access.nullsignal.games/CompRules/Null-Signal-Games-Netrunner-Comprehensive-Rules-v23.08.pdf), which was released on 9 December 2022.

**Rules mentioned:**  
*Chapter 8: Card Manipulation*  
[8.6.6e](https://rules.nullsignal.games/?r=rule_steps_playing_played_checkpoint) (p.56)  
[8.6.6f](https://rules.nullsignal.games/?r=rule_steps_playing_resolve_play_abilities) (p.56)  

**Cards mentioned:**  
[Diesel](https://netrunnerdb.com/en/card/31027)  
[Legwork](https://netrunnerdb.com/en/card/31019)  
[Excalibur](https://netrunnerdb.com/en/card/29017)  
[Economic Warfare](https://netrunnerdb.com/en/card/21036)  
[Scavenge](https://netrunnerdb.com/en/card/03034)  
[Rejig](https://netrunnerdb.com/en/card/26029)  
[Simulchip](https://netrunnerdb.com/en/card/26085)  
[Reconstruction Contract](https://netrunnerdb.com/en/card/21020)  
[Bacterial Programming](https://netrunnerdb.com/en/card/21033)  
[Ganked!](https://netrunnerdb.com/en/card/26119)  
[Ansel](https://netrunnerdb.com/en/card/30038)  
[Always Have a Backup Plan](https://netrunnerdb.com/en/card/26011)  
[The Class Act](https://netrunnerdb.com/en/card/26018)  
[DaVinci](https://netrunnerdb.com/en/card/08107)  
[Whistleblower](https://netrunnerdb.com/en/card/26030)  
[Ampére](https://netrunnerdb.com/en/card/33128)  
[Red Level Clearance](https://netrunnerdb.com/en/card/26037)  
[Game Over](https://netrunnerdb.com/en/card/26053)  
[Vulnerability Audit](https://netrunnerdb.com/en/card/26063)  
[Hoshiko Shiro](https://netrunnerdb.com/en/card/26066)  
[Harmony AR Therapy](https://netrunnerdb.com/en/card/26083)  
[Test Run](https://netrunnerdb.com/en/card/31028)  
[Engram Flush](https://netrunnerdb.com/en/card/26108)  
[Hyoubu Precog Manifold](https://netrunnerdb.com/en/card/26110)  
[La Costa Grid](https://netrunnerdb.com/en/card/27005)  
[SYNC Rerouting](https://netrunnerdb.com/en/card/26118)  
[Data Raven](https://netrunnerdb.com/en/card/25112)  
[Funhouse](https://netrunnerdb.com/en/card/30054)  
[Lucky Charm](https://netrunnerdb.com/en/card/26014)  
[Transport Monopoly](https://netrunnerdb.com/en/card/26121)  
[Wall to Wall](https://netrunnerdb.com/en/card/26122)  
[Winchester](https://netrunnerdb.com/en/card/26125)  
[Starlit Knight](https://netrunnerdb.com/en/card/34053)  
["Baklan" Bochkin](https://netrunnerdb.com/en/card/26017)  
[Lat](https://netrunnerdb.com/en/card/26019)  
[Focus Group](https://netrunnerdb.com/en/card/26052)  
[The Back](https://netrunnerdb.com/en/card/26082)  
[Gachapon](https://netrunnerdb.com/en/card/26069)  
[Aiki](https://netrunnerdb.com/en/card/11032)  
[Euler](https://netrunnerdb.com/en/card/26087)  
[Penrose](https://netrunnerdb.com/en/card/26089)  
[Utae](https://netrunnerdb.com/en/card/26005)  
[Odore](https://netrunnerdb.com/en/card/26071)  

**Other:**  
[Downfall Release Notes](https://nullsignal.games/products/Downfall/DFReleaseNotes/)  
[rules.nullsignal.games](https://rules.nullsignal.games/)  

## Acknowledgements
Thanks again to Jamie for answering way too many questions.

### Footnotes
[^1]: The corp "winning" the psi game on Aiki makes the runner draw cards, which is to their benefit most of the time, but in the context of this specific card, it contributes to the mill game plan it's intended to synergize with.