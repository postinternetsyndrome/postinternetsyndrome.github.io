---
layout: post
title:  "The Parhelion unofficial comprehensive release notes II: Cards"
date:   2023-02-16 12:00:00
categories: release-notes
tags: [cr, cr-22.12, ctu, ctu-1.3, ctu-22.12]
---

*“My onboard memory store is more than capable of handling all the mission requirements.”  
– HAL 9000*

On December 20 2022 NSG released a new version of the Card Text Updates (CTU) document. It contains 43 new entries and 50 updated ones, bringing the size of the document up to 134 pages from the previous 117. Most of the changes are simple housekeeping stuff, like replacing all instances of "brain damage" with the new term "[Core damage](#core-damage)", but some of them are more interesting, and in this article I'll list all cards that have received changes and how they are relevant to you.

Like the Comprehensive Rules, the CTU document has a new versioning format. The last one was version 1.3, but the new is version 22.12 (referring to the year and the month of its release), which is the same as its corresponding CR version.

### Contents
- [What you need to know](#what-you-need-to-know)  
- [Cards added](#cards-added)  
- [Cards updated](#cards-updated)  
- [Categories](#categories)
  - [Core damage](#core-damage)
  - [Caïssa](#caïssa)
  - [This [card type]](#this-card-type)
  - [Ability ordering](#ability-ordering)
  - [Take -> suffer](#take---suffer)
  - [Ability removal](#ability-removal)
  - [Trojan](#trojan)
  - [Has -> gets](#has---gets)
  - [Installed](#installed)
  - [X](#x)
  - [Interrupt](#interrupt)
  - [Server or root](#server-or-root)
  - [Choosing servers](#choosing-servers)
  - [General consistency](#general-consistency)
- [Individual cards](#individual-cards)
  - [Bloom](#bloom)
  - [EMP Device](#emp-device)
  - [Ika](#ika)
  - [Malia Z0l0k4](#malia-z0l0k4)
  - [Mausolus](#mausolus)
  - [Monolith](#monolith)
  - [NEXT Wave 2](#next-wave-2)
  - [Spinal Modem](#spinal-modem)
  - [Skulljack](#skulljack)
  - [Wetwork Refit](#wetwork-refit)

> **Update 2023-02-21** 
- Rewrote the Ika section since I didn't realize it was actually the very final card to receive the interface treatment.

> **Update 2024-08-15**
- Removed the Ika section since I didn't realize it was actually just getting a trojan subtype, it already had the interface text, ever since [CTU 1.0](https://nullsignal.games/wp-content/uploads/2021/08/NISEI-Card-Updates-v1.0.pdf).

## What you need to know
There are relatively few changes of particular note in this CTU, which to many will be good news. We were spared this time the type of stealth functional changes that in previous CTUs have occasionally snuck in under the radar and surprised people in tournaments.

The main exhibits are the changes to [wordings regarding positions](#bloom) and [installed states](#installed) that are relevant to [ZATO City Grid](https://netrunnerdb.com/en/card/33127) and [Nanisivik Grid](https://netrunnerdb.com/en/card/33111). The rest may be considered esoterica, mainly of interest to rules nerds (but you're reading this, aren't you).

One card which has been the subject of a lot of debate over the years is [Warroid Tracker](https://netrunnerdb.com/en/card/12068). Some frequenters of rules questions threads might be glad to see it getting an update to make it more clear [exactly when its ability applies](#server-or-root). Along with the recently [updated rules](/release-notes/parhelion-release-notes-i/#466g-i-j---expanded), there should no longer be any ambiguities left regarding the function of this card and other similar ones.

The changed cards are listed below with a link to their CTU entry, and a list of categories linking to explanatory sections later in the article.

## Cards added
The following 43 cards which were previously unaltered have received new official text.

**[Amped Up](/ctu/22.12.html#pf5)** - *[Core damage](#core-damage)*  
**[Bishop](/ctu/22.12.html#pfb)** - *[Caïssa](#caïssa), [Trojan](#trojan), [This [card type]](#this-card-type), [Ability ordering](#ability-ordering)*  
**[Black Level Clearance](/ctu/22.12.html#pfc)** - *[This [card type]](#this-card-type), [Core damage](#core-damage), [Take -> suffer](#take---suffer)*  
**[Bloom](/ctu/22.12.html#pfd)** - *[Next innermost position -> directly inward](#bloom)*  
**[Botulus](/ctu/22.12.html#pfe)** - *[Trojan](#trojan)*  
**[Brain Cage](/ctu/22.12.html#pfe)** - *[Has -> gets](#has---gets), [Core damage](#core-damage), [Ability ordering](#ability-ordering)*  
**[Brainstorm](/ctu/22.12.html#pff)** - *[Core damage](#core-damage), [X](#x)*  
**[Bullfrog](/ctu/22.12.html#pf10)** - *[This [card type]](#this-card-type), [Installed](#installed)*  
**[Caldera](/ctu/22.12.html#pf11)** - *[Interrupt](#interrupt), [Core damage](#core-damage)*  
**[Cerebral Overwriter](/ctu/22.12.html#pf14)** - [Core damage](#core-damage), *[Installed](#installed)*  
**[Cerebral Static](/ctu/22.12.html#pf14)** - *[This [card type]](#this-card-type), [Ability removal](#ability-removal)*  
**[Chisel](/ctu/22.12.html#pf15)** - *[Trojan](#trojan)*, *[Has -> gets](#has---gets)*  
**[Chrome Parlor](/ctu/22.12.html#pf15)** - *[Interrupt](#interrupt)*  
**[Dr. Lovegood](/ctu/22.12.html#pf20)** - *[Ability removal](#ability-removal)*  
**[Edge Of World](/ctu/22.12.html#pf22)** - *[Core damage](#core-damage), [General consistency](#general-consistency)*  
**[Egret](/ctu/22.12.html#pf22)** - *[Trojan](#trojan)*  
**[EMP Device](/ctu/22.12.html#pf23)** - *[Weapon subtype](#emp-device)*  
**[Employee Strike](/ctu/22.12.html#pf23)** - *[This [card type]](#this-card-type), [Ability removal](#ability-removal)*  
**[Feedback Filter](/ctu/22.12.html#pf2a)** - *[Interrupt](#interrupt), [Core damage](#core-damage)*  
**[Fenris](/ctu/22.12.html#pf2a)** - *[This [card type]](#this-card-type), [Core damage](#core-damage)*  
**[Jemison Astronautics](/ctu/22.12.html#pf3d)** - *[X](#x)*  
**[Komainu](/ctu/22.12.html#pf42)** - *[X](#x)*  
**[Kuwinda K4h1u3](/ctu/22.12.html#pf42)** - *[Core damage](#core-damage)  
**[Kyuban](/ctu/22.12.html#pf42)** - *[Trojan](#trojan), [General consistency](#general-consistency)*  
**[Mausolus](/ctu/22.12.html#pf47)** - *[System Update wording](#mausolus)*  
**[Monolith](/ctu/22.12.html#pf4b)** - *[This [card type]](#this-card-type), [Interrupt](#interrupt), [Core damage](#core-damage), [Cost reduction](#monolith)*  
**[Next Diamond](/ctu/22.12.html#pf52)** - *[This [card type]](#this-card-type), [Core damage](#core-damage)*  
**[Next Wave 2](/ctu/22.12.html#pf52)** - *[This [card type]](#this-card-type), [Core damage](#core-damage), [Moved condition](#next-wave-2)*  
**[Parasite](/ctu/22.12.html#pf57)** - *[This [card type]](#this-card-type), [Trojan](#trojan), [General consistency](#general-consistency), [Has -> gets](#has---gets)*  
**[Puffer](/ctu/22.12.html#pf5f)** - *[Ability ordering](#ability-ordering)*  
**[Ramujan-reliant 550 Bmi](/ctu/22.12.html#pf61)** - *[Interrupt](#interrupt), [Core damage](#core-damage), [General consistency](#general-consistency)*  
**[Rook](/ctu/22.12.html#pf64)** - *[Caïssa](#caïssa), *[Trojan](#trojan)*, [This [card type]](#this-card-type), [Ability ordering](#ability-ordering)*   
**[Rumor Mill](/ctu/22.12.html#pf65)** - *[Ability removal](#ability-removal)*  
**[Ryon Knight](/ctu/22.12.html#pf65)** - *[Core damage](#core-damage)*  
**[Sand Storm](/ctu/22.12.html#pf67)** - *[This [card type]](#this-card-type), [Installed](#installed)*  
**[Sentinel Defense Program](/ctu/22.12.html#pf69)** - *[Core damage](#core-damage)*  
**[Skulljack](/ctu/22.12.html#pf6d)** - *[This [card type]](#this-card-type), [Core damage](#core-damage), [Corp cards only](#skulljack)*  
**[Spinal Modem](/ctu/22.12.html#pf6e)** - *[Core damage](#core-damage), [Spending hosted credits](#spinal-modem)*  
**[Stim Dealer](/ctu/22.12.html#pf70)** - *[Core damage](#core-damage), [General consistency](#general-consistency), [This [card type]](#this-card-type)*  
**[Tranquilizer](/ctu/22.12.html#pf79)** - *[Trojan](#trojan)*  
**[Trypano](/ctu/22.12.html#pf7a)** - *[This [card type]](#this-card-type), [Ability ordering](#ability-ordering), [Trojan](#trojan)*  
**[Wetwork Refit](/ctu/22.12.html#pf82)** - *[Core damage](#core-damage), [No longer installed](#wetwork-refit)*  
**[Wotan](/ctu/22.12.html#pf83)** - *[Core damage](#core-damage)*  

## Cards updated
The following 50 cards which were already in the CTU document have had their official text updated:

**[Ben Musashi](/ctu/22.12.html#pfa)** - *[Server or root](#server-or-root)*  
**[Cerebral Cast](/ctu/22.12.html#pf13)** - *[Core damage](#core-damage)*  
**[Cold Read](/ctu/22.12.html#pf17)** - *[Installed](#installed)*  
**[Defective Brainchips](/ctu/22.12.html#pf1c)** - *[Core damage](#core-damage)*  
**[Enforcer 1.0](/ctu/22.12.html#pf24)** - *[Core damage](#core-damage)*  
**[Executive Functioning](/ctu/22.12.html#pf26)** - *[Core damage](#core-damage)*  
**[Fairchild 2.0](/ctu/22.12.html#pf28)** - *[Core damage](#core-damage)*  
**[Fairchild 3.0](/ctu/22.12.html#pf29)** - *[Core damage](#core-damage)*  
**[Fairchild](/ctu/22.12.html#pf27)** - *[Core damage](#core-damage)*  
**[Heimdall 1.0](/ctu/22.12.html#pf33)** - *[Core damage](#core-damage)*  
**[Heimdall 2.0](/ctu/22.12.html#pf33)** - *[Core damage](#core-damage)*  
**[Ichi 1.0](/ctu/22.12.html#pf38)** - *[Core damage](#core-damage)*  
**[Ichi 2.0](/ctu/22.12.html#pf38)** - *[Core damage](#core-damage)*  
**[Ika](/ctu/22.12.html#pf39)** - *[Trojan](#trojan)*  
**[Janus 1.0](/ctu/22.12.html#pf3d)** - *[Core damage](#core-damage)*  
**[Kamali 1.0](/ctu/22.12.html#pf3f)** - *[Core damage](#core-damage)*  
**[Kill Switch](/ctu/22.12.html#pf40)** - *[This [card type]](#this-card-type), [Core damage](#core-damage)*  
**[Knight](/ctu/22.12.html#pf41)** - *[Caïssa](#caïssa)*, *[Trojan](#trojan)*  
**[Malia Z0l0k4](/ctu/22.12.html#pf45)** - *[An -> 1](#malia-z0l0k4)*  
**[Muresh Bodysuit](/ctu/22.12.html#pf4c)** - *[Take -> suffer](#take---suffer)*  
**[Negotiator](/ctu/22.12.html#pf4f)** - *[Installed](#installed), [General consistency](#general-consistency)*  
**[Nerine 2.0](/ctu/22.12.html#pf4f)** - *[Core damage](#core-damage)*  
**[Net Shield](/ctu/22.12.html#pf50)** - *[Take -> suffer](#take---suffer)*  
**[Nihongai Grid](/ctu/22.12.html#pf53)** - *[General consistency](#general-consistency)*  
**[Old Hollywood Grid](/ctu/22.12.html#pf55)** - *[Server or root](#server-or-root)*  
**[Overseer Matrix](/ctu/22.12.html#pf56)** - *[Server or root](#server-or-root)*  
**[Patron](/ctu/22.12.html#pf58)** - *[Choosing servers](#choosing-servers)*  
**[Pawn](/ctu/22.12.html#pf58)** - *[Trojan](#trojan)*, *[This [card type]](#this-card-type)*  
**[Power Grid Overload](/ctu/22.12.html#pf5c)** - *[Installed](#installed)*  
**[Red Herrings](/ctu/22.12.html#pf62)** - *[Server or root](#server-or-root)*  
**[Riot Suppression](/ctu/22.12.html#pf63)** - *[Core damage](#core-damage)*  
**[Security Testing](/ctu/22.12.html#pf68)** - *[Choosing servers](#choosing-servers)*  
**[Shi.Kyū](/ctu/22.12.html#pf6b)** - *[Take -> suffer](#take---suffer)*  
**[Stimhack](/ctu/22.12.html#pf70)** - *[Core damage](#core-damage), [General consistency](#general-consistency)*  
**[Strongbox](/ctu/22.12.html#pf71)** - *[Server or root](#server-or-root)*  
**[Study Guide](/ctu/22.12.html#pf71)** - *[Ability ordering](#ability-ordering)*  
**[Tempus](/ctu/22.12.html#pf74)** - *[Core damage](#core-damage)*  
**[Tori Hanzō](/ctu/22.12.html#pf78)** - *[Core damage](#core-damage), [General consistency](#general-consistency)*  
**[Tracker](/ctu/22.12.html#pf79)** - *[Choosing servers](#choosing-servers)*  
**[Týr](/ctu/22.12.html#pf7b)** - *[Core damage](#core-damage)*  
**[Under the Bus](/ctu/22.12.html#pf7c)** - *[Installed](#installed)*  
**[Vaporframe Fabricator](/ctu/22.12.html#pf7e)** - *[Server or root](#server-or-root)*  
**[Vikram 1.0](/ctu/22.12.html#pf7f)** - *[Core damage](#core-damage)*  
**[Viktor 1.0](/ctu/22.12.html#pf80)** - *[Core damage](#core-damage)*  
**[Viktor 2.0](/ctu/22.12.html#pf80)** - *[Core damage](#core-damage)*  
**[Warroid Tracker](/ctu/22.12.html#pf81)** - *[Server or root](#server-or-root)*  
**[Will-o'-the-Wisp](/ctu/22.12.html#pf82)** - *[General consistency](#general-consistency)*  
**[Wireless Net Pavilion](/ctu/22.12.html#pf83)** - *[Installed](#installed)*  
**[Zed 1.0](/ctu/22.12.html#pf84)** - *[Core damage](#core-damage), [General consistency](#general-consistency)*  
**[Zed 2.0](/ctu/22.12.html#pf85)** - *[Core damage](#core-damage)*  

## Categories
Most of the changes can be sorted into one of a number of different categories. These categories are listed below, along with the affected cards.

### Core damage
The change of all older mentions of "brain damage" to the newer "core damage" didn't make it into the [last CTU](https://nullsignal.games/wp-content/uploads/2022/06/NISEI-Card-Text-Updates-v1.3.pdf), but now they're here, and they make up about half of all changed cards this time.

Amped Up  
Brain Cage  
Brainstorm  
Caldera  
Cerebral Cast  
Cerebral Overwriter  
Defective Brainchips  
Edge Of World  
Enforcer 1.0  
Executive Functioning  
Fairchild  
Fairchild 2.0  
Fairchild 3.0  
Feedback Filter  
Fenris  
Heimdall 1.0  
Heimdall 2.0  
Ichi 1.0  
Ichi 2.0  
Janus 1.0  
Kamali 1.0  
Kill Switch  
Kuwinda K4h1u3  
Monolith  
Nerine 2.0  
Next Diamond  
Next Wave 2  
Ramujan-reliant 550 Bmi  
Riot Suppression  
Ryon Knight  
Sentinel Defense Program  
Skulljack  
Spinal Modem  
Stim Dealer  
Stimhack  
Tempus  
Tori Hanzō  
Týr  
Vikram 1.0  
Viktor 1.0  
Viktor 2.0  
Wetwork Refit  
Wotan  
Zed 1.0  
Zed 2.0  

### Caïssa
Several of the caïssa programs have had their abilities restructured. The restrictions on hosting that apply when the card is already hosted have been broken out into a separate ability rather than being part of the click ability that hosts them.

Bishop  
Knight  
Rook  

### Trojan
All existing programs that host themselves on ice have received the [previously announced](https://nullsignal.games/blog/remastering-system-gateway/) addition of the "trojan" subtype.

Bishop  
Botulus  
Chisel  
Egret  
Ika  
Knight  
Kyuban  
Parasite  
Pawn  
Rook  
Tranquilizer  
Trypano  

### This [card type]
As part of the ongoing project to harmonize self-references, a number of cards which previously said "this card" or "[card name]" have been updated to say "this [card type]", which is the standard used by all newly released NSG cards.

Bishop  
Black Level Clearance  
Bullfrog  
Cerebral Static  
Employee Strike  
Fenris  
Kill Switch  
Monolith  
Next Diamond  
Next Wave 2  
Parasite  
Rook  
Sand Storm  
Skulljack  
Stim Dealer  
Trypano  

### Ability ordering
A number of cards have had the order of their abilities switched around, for consistency. The tendency we're moving towards is that static abilities are placed at the top, with paid abilities below.

Bishop  
Brain Cage  
Puffer  
Rook  
Study Guide  
Trypano  

### Take -> suffer
Cards which used to refer to "taking" damage are being migrated to the term "suffer", which was sometimes used even during FFG days, but is now being standardized as the single word to be used for this effect.

Black Level Clearance  
Muresh Bodysuit  
Net Shield  
Shi.Kyū  

### Ability removal
A number of cards which used the older wording of turning the text boxes of other cards "blank" have been updated to the more modern "loses printed abilities", which is the terminology used on newer cards. This change has previously been applied to [Malia Z0l0k4](https://netrunnerdb.com/en/card/21069) as well, and there are now no longer any cards using the "text box is blank" wording.

Cerebral Static  
Dr. Lovegood  
Employee Strike  
Rumor Mill  

### Has -> gets
NSG has generally adopted the word "gets" instead of "has" for static value modifications. This new wording has previously been applied to [SanSan City Grid](https://netrunnerdb.com/en/card/31069) and a whole slew of other cards. It has now also been added to Chisel and Parasite.

Brain Cage  
Chisel  
Parasite  

### Installed
Eight cards have received an additional qualifier that they or the target of their abilities must be installed. This serves to clarify how certain ice cards interacts with ZATO City Grid and Nanisivik Grid for example, but it has been added to a number of non-ice cards as well. In most cases this is not a functional change, since the targeting rules state that only ["counters in the play area and installed cards"](/cr/22.12.html#pf14) are valid targets unless the ability specifies otherwise.

In the specific case of [Cerebral Overwriter](https://netrunnerdb.com/en/card/26099), this is technically a functional change, since it could in theory be triggered when accessed from HQ or R&D. In practice though, you would always be forbidden from actually using it due to [NCIGS](/essays/cost-and-effect), so that distinction is not very important. It also lacks the standard "must be revealed if accessed" text which cards intended to be triggered from hidden locations tends to have, clearly indicating that it was never intended to trigger from a non-installed state.

Bullfrog  
Cerebral Overwriter  
Cold Read  
Negotiator  
Power Grid Overload  
Sand Storm  
Under the Bus  
Wireless Net Pavilion  

### X
Four cards which didn't before now use "X" to determine the number of something, rather than "for each" and similar. This is facilitated by the [new rule](/release-notes/parhelion-release-notes-i//#9122e---expanded) which defines the value of X in situations where it can't otherwise be determined.

Brainstorm  
Jemison Astronautics  
Komainu  

### Interrupt
A number of cards with prevention effects have had the interrupt glyph added to their official text. For most of these it's just a simple addition of a new icon, but Chrome Parlor has also been rewritten in a more standardized conditional ability form, instead of the old wording which looked more like a static ability. It also now prevents all damage universally, without naming specific forms (which makes it indirectly part of the "core damage" rework).

Caldera  
Chrome Parlor  
Feedback Filter  
Monolith  
Ramujan-reliant 550 BMI  

### Server or root
The term "from this server" was never clearly defined (it's not mentioned in the CR) and has led to a lot of questions about the scope of certain cards. Six of those cards have now been updated to say "from this server or its root", to make it clear that cards in the root are also covered by their abilities. Whether this means that "from this server" should now be understood to only mean exactly "cards in Archives, R&D or HQ" is not yet entirely clear ([Arella Salvatore](https://netrunnerdb.com/en/card/22049) and [Malapert Data Vault](https://netrunnerdb.com/en/card/30066) still use "from this server" to refer to the server root, so presumably the old, wide meaning is still in force), but at least there's no longer any ambiguity about what the individual cards do.

Ben Musashi  
Old Hollywood Grid  
Overseer Matrix  
Red Herrings  
Strongbox  
Warroid Tracker  

### Choosing servers
All three existing cards which choose a server at the beginning of your turn have been rewritten to take advantage of the simplified rule [9.10.3b](/release-notes/parhelion-release-notes-i#9103b---revised). There's no longer any need to specify that the ability expires "this turn" since it now does that implicitly.

In addition, choosing a server for Tracker is now optional, the same change as Security Testing got when it was included in System Update. With that adjustment, all four cards that choose a target server at the beginning of your turn (Security Testing, Patron, Tracker and [Tsakhia "Bankhar" Gantulga](https://netrunnerdb.com/en/card/33074)) now use the same wording. Patron was worded as an optional choice from the start, and NSG have chosen to adopt this as the standard moving forward.

As a side note, with the new [OP policies that were introduced recently](https://nullsignal.games/blog/organized-play-policies-update-takebacks-and-missed-triggers/), the difference between mandatory and optional abilities is no longer as relevant for competitive play, but we can still find the consistency aesthetically pleasing.

Patron  
Security Testing  
Tracker  

### General consistency
A number of eclectic wordings have been changed to standard NSG terminology for general consistency reasons. These are mostly small grammatical nudges that do not change the semantics of the cards in any meaningful way.

Edge Of World  
Kyuban  
Negotiator  
Nihongai Grid  
Parasite  
Ramujan-reliant 550 BMI  
Stim Dealer  
Stimhack  
Tori Hanzō  
Will-o'-the-Wisp  
Zed 1.0  

## Individual cards
A handful of cards have received bespoke changes that resisted categorization.

### Bloom
The second subroutine on Bloom has been updated to say "directly inward from this ice" instead of "in the next innermost position". This should make it more clear that the subroutine does not function when fired by ZATO or Nanisivik.

### EMP Device
This card has had the Bomb subtype removed and replaced by Weapon. This is technically a functional change, making the card tutorable by [Asmund Pudlat](https://netrunnerdb.com/en/card/33082), but it's obviously mostly for flavor and consistency reasons.

### Malia Z0l0k4
"An" has been replaced with "1". NSG are generally moving towards specifying quantities with numbers rather than text.

### Mausolus
Mausolus has been updated to the more modern wording already used by [Hortum](https://netrunnerdb.com/en/card/31076) and [Colossus](https://netrunnerdb.com/en/card/26124). Those two were [reprinted in System Update](https://nullsignal.games/blog/su21-corp-spoilers/) and had their wording changed simultaneously. Mausulous was already informally considered to work the same way, but has now been officially brought up to speed.

### Monolith
NSG have been moving away from the wording "lowering the install cost", opting instead for the phrasing "paying X less". Monolith has now been updated to this new style. This wording could have slight implications for cards that care about the install cost of other cards; if you are merely "paying less", you don't have to worry about there possibly being a short instant in time where the actual install cost of the card is different from the printed one. It seems unlikely that a card would ever be printed that cared about such an ephemeral game state change, but stranger things have happened.

### NEXT Wave 2
As part of a general style shift, the additional condition "if there is a rezzed piece of NEXT ice" has been moved from the trigger condition of NEXT Wave 2 and into the effect itself. The rules team has stated that this is mainly for style reasons, but it has minor mechanical implications. There was an old ruling - still listed on NRDB up until very recently - that you can't use [24/7 News Cycle](https://netrunnerdb.com/en/card/09019) with agendas which don't have an "explicit" "when scored" ability. NEXT Wave 2 used to be one of these, but with this wording change can now be used with 24/7, giving corps access to a method to proactively deal core damage in eternal.

### Spinal Modem
Spinal Modem now says "you can spend hosted credits" rather than "use these credits". This wording was previously applied to [Simone Diego](https://netrunnerdb.com/en/card/02099) as well, and is the standard way NSG implements spendable credits not in your credit pool now.

### Skulljack
Apart from the general templating changes, Skulljack has also received the minor modification of only affecting the trash cost of Corp cards. The old wording said "all cards", which is for all practical purposes identical to the new one since only corp cards have trash costs anyway, but presumably this change was made for style reasons.

(We will all look back on this day when NSG inevitably prints runner cards that get installed in servers and can be accessed, at which point we'll realize that they wisely reined in Skulljack preemptively to prevent it from taking over the meta.)

### Wetwork Refit
Wetwork Refit was reworded to no longer mention being installed in the text. This is part of a general shift in how condition counters are treated, I've been told in informal conversations with the rules team. In the future, condition counters will never be installed, but this has not been officially communicated and there's no guarantee they won't change their minds again before the next version of the rules is published. Furthermore, the rules and card texts are not currently entirely consistent with this stated paradigm:

> [***CR 1.13.5d***](/cr/22.12.html#pf11) "Some operations and events convert themselves into condition counters and install themselves hosted onto other cards."

It is currently a matter of interpretation whether this particular text update constitutes a functional change, or if 1.13.5d ensures that the counter is still installed, but I believe the latter is the intended reading. Expect further changes on this one.

---

## References
This article uses the [NSG Comprehensive Rules Document version 22.12](https://nullsignal.games/wp-content/uploads/2022/12/Null-Signal-Games-Netrunner-Comprehensive-Rules-v22.12.pdf), which was released on 9 December 2022.

For convenience of linking, this article also uses hosted versions of [CR 22.12](/cr/22.12.html) and [CTU 22.12](/ctu/22.12.html). These are identical to the PDF documents found on the NSG site, but I can't guarantee that my own hosted materials are always up to date, so when in doubt, always refer to the official versions.

**Rules mentioned:**  
*Chapter 1: Game Concepts*  
1.13.5d (p.17)
1.15.2d (p.20)  

*Chapter 4: Game Zones*  
4.6.6i (p.47)  
4.6.6j (p.47)  

*Chapter 9: Abilities*  
9.10.3b (p.112)

**Cards mentioned:**  
[ZATO City Grid](https://netrunnerdb.com/en/card/33127)  
[Nanisivik Grid](https://netrunnerdb.com/en/card/33111)  
[Warroid Tracker](https://netrunnerdb.com/en/card/12068)  
[Amped Up](https://netrunnerdb.com/en/card/07031)  
[Bishop](https://netrunnerdb.com/en/card/04021)  
[Black Level Clearance](https://netrunnerdb.com/en/card/13039)  
[Bloom](https://netrunnerdb.com/en/card/12032)  
[Botulus](https://netrunnerdb.com/en/card/30004)  
[Brain Cage](https://netrunnerdb.com/en/card/08049)  
[Brainstorm](https://netrunnerdb.com/en/card/10086)  
[Bullfrog](https://netrunnerdb.com/en/card/02073)  
[Caldera](https://netrunnerdb.com/en/card/12105)  
[Cerebral Overwriter](https://netrunnerdb.com/en/card/26099)  
[Cerebral Static](https://netrunnerdb.com/en/card/06025)  
[Chisel](https://netrunnerdb.com/en/card/26003)  
[Chrome Parlor](https://netrunnerdb.com/en/card/26003)  
[Dr. Lovegood](https://netrunnerdb.com/en/card/09042)  
[Edge Of World](https://netrunnerdb.com/en/card/02053)  
[Egret](https://netrunnerdb.com/en/card/31032)  
[EMP Device](https://netrunnerdb.com/en/card/10020)  
[Employee Strike](https://netrunnerdb.com/en/card/09053)  
[Feedback Filter](https://netrunnerdb.com/en/card/03037)  
[Fenris](https://netrunnerdb.com/en/card/04071)  
[Jemison Astronautics](https://netrunnerdb.com/en/card/12016)  
[Komainu](https://netrunnerdb.com/en/card/05017)  
[Kuwinda K4h1u3](https://netrunnerdb.com/en/card/21049)  
[Kyuban](https://netrunnerdb.com/en/card/22020)  
[Mausolus](https://netrunnerdb.com/en/card/11097)  
[Monolith](https://netrunnerdb.com/en/card/03036)  
[Next Diamond](https://netrunnerdb.com/en/card/21112)  
[Next Wave 2](https://netrunnerdb.com/en/card/12009)  
[Parasite](https://netrunnerdb.com/en/card/29002)  
[Puffer](https://netrunnerdb.com/en/card/21004)  
[Ramujan-reliant 550 Bmi](https://netrunnerdb.com/en/card/10002)  
[Rook](https://netrunnerdb.com/en/card/04003)  
[Rumor Mill](https://netrunnerdb.com/en/card/11022)  
[Ryon Knight](https://netrunnerdb.com/en/card/08054)  
[Sand Storm](https://netrunnerdb.com/en/card/12114)  
[Sentinel Defense Program](https://netrunnerdb.com/en/card/03007)  
[Skulljack](https://netrunnerdb.com/en/card/08042)  
[Spinal Modem](https://netrunnerdb.com/en/card/20007)  
[Stim Dealer](https://netrunnerdb.com/en/card/07051)  
[Tranquilizer](https://netrunnerdb.com/en/card/30017)  
[Trypano](https://netrunnerdb.com/en/card/21082)  
[Wetwork Refit](https://netrunnerdb.com/en/card/11071)  
[Wotan](https://netrunnerdb.com/en/card/04030)  
[Ben Musashi](https://netrunnerdb.com/en/card/12054)  
[Cerebral Cast](https://netrunnerdb.com/en/card/05013)  
[Cold Read](https://netrunnerdb.com/en/card/11083)  
[Defective Brainchips](https://netrunnerdb.com/en/card/08072)  
[Enforcer 1.0](https://netrunnerdb.com/en/card/08089)  
[Executive Functioning](https://netrunnerdb.com/en/card/13035)  
[Fairchild 2.0](https://netrunnerdb.com/en/card/11031)  
[Fairchild 3.0](https://netrunnerdb.com/en/card/11049)  
[Fairchild](https://netrunnerdb.com/en/card/11089)  
[Heimdall 1.0](https://netrunnerdb.com/en/card/25074)  
[Heimdall 2.0](https://netrunnerdb.com/en/card/03015)  
[Ichi 1.0](https://netrunnerdb.com/en/card/25075)  
[Ichi 2.0](https://netrunnerdb.com/en/card/03017)  
[Ika](https://netrunnerdb.com/en/card/22019)  
[Janus 1.0](https://netrunnerdb.com/en/card/02012)  
[Kamali 1.0](https://netrunnerdb.com/en/card/21092)  
[Kill Switch](https://netrunnerdb.com/en/card/21070)  
[Knight](https://netrunnerdb.com/en/card/04043)  
[Malia Z0l0k4](https://netrunnerdb.com/en/card/21069)  
[Muresh Bodysuit](https://netrunnerdb.com/en/card/02044)  
[Negotiator](https://netrunnerdb.com/en/card/08019)  
[Nerine 2.0](https://netrunnerdb.com/en/card/12030)  
[Net Shield](https://netrunnerdb.com/en/card/01045)  
[Nihongai Grid](https://netrunnerdb.com/en/card/11093)  
[Old Hollywood Grid](https://netrunnerdb.com/en/card/08097)  
[Overseer Matrix](https://netrunnerdb.com/en/card/21100)  
[Patron](https://netrunnerdb.com/en/card/10063)  
[Pawn](https://netrunnerdb.com/en/card/04002)  
[Power Grid Overload](https://netrunnerdb.com/en/card/02037)  
[Red Herrings](https://netrunnerdb.com/en/card/25121)  
[Riot Suppression](https://netrunnerdb.com/en/card/21113)  
[Security Testing](https://netrunnerdb.com/en/card/31024)  
[Shi.Kyū](https://netrunnerdb.com/en/card/05011)  
[Stimhack](https://netrunnerdb.com/en/card/25007)  
[Strongbox](https://netrunnerdb.com/en/card/20076)  
[Study Guide](https://netrunnerdb.com/en/card/08028)  
[Tempus](https://netrunnerdb.com/en/card/21071)  
[Tori Hanzō](https://netrunnerdb.com/en/card/05022)  
[Tracker](https://netrunnerdb.com/en/card/11105)  
[Týr](https://netrunnerdb.com/en/card/26102)  
[Under the Bus](https://netrunnerdb.com/en/card/22057)  
[Vaporframe Fabricator](https://netrunnerdb.com/en/card/26100)  
[Vikram 1.0](https://netrunnerdb.com/en/card/10012)  
[Viktor 1.0](https://netrunnerdb.com/en/card/25078)  
[Viktor 2.0](https://netrunnerdb.com/en/card/03019)  
[Will-o'-the-Wisp](https://netrunnerdb.com/en/card/06032)  
[Wireless Net Pavilion](https://netrunnerdb.com/en/card/08108)  
[Zed 1.0](https://netrunnerdb.com/en/card/03020)  
[Zed 2.0](https://netrunnerdb.com/en/card/12010)  
[SanSan City Grid](https://netrunnerdb.com/en/card/31069)  
[Arella Salvatore](https://netrunnerdb.com/en/card/22049)  
[Malapert Data Vault](https://netrunnerdb.com/en/card/30066)  
[Tsakhia "Bankhar" Gantulga](https://netrunnerdb.com/en/card/33074)  
[Asmund Pudlat](https://netrunnerdb.com/en/card/33082)  
[Hortum](https://netrunnerdb.com/en/card/31076)  
[Colossus](https://netrunnerdb.com/en/card/26124)  
[24/7 News Cycle](https://netrunnerdb.com/en/card/09019)  
[Simone Diego](https://netrunnerdb.com/en/card/02099)  

**Other:**  
[NSG Card Text Updates Document version 22.12](https://nullsignal.games/wp-content/uploads/2022/12/Null-Signal-Games-Netrunner-Card-Text-Updates-v22.12.pdf)  
[NSG Card Text Updates Document version 1.3](https://nullsignal.games/wp-content/uploads/2022/06/NISEI-Card-Text-Updates-v1.3.pdf)  
[NSG Card Text Updates Document version 1.0](https://nullsignal.games/wp-content/uploads/2021/08/NISEI-Card-Updates-v1.0.pdf)  
[Remastering System Gateway](https://nullsignal.games/blog/remastering-system-gateway/), NSG blog post  

## Acknowledgements
*Proofreading & factchecking*  
Cephalopod Wizard  
tbu3k  
coldlava  
JayPumpkin  