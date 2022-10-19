# Ahungry Tweaks

Various tweaks that I want in my own setup, and may be useful in yours.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [Ahungry Tweaks](#ahungry-tweaks)
- [Components](#components)
    - [Balance Item +APR (cap +APR at 1/2 APR per item, replace w/ thac0 + dmg bonuses)](#balance-item-apr-cap-apr-at-12-apr-per-item-replace-w-thac0--dmg-bonuses)
    - [Creatures](#creatures)
        - [Remove backstab immunity from creatures (not classes/items)](#remove-backstab-immunity-from-creatures-not-classesitems)
        - [Remove timestop immunity from creatures](#remove-timestop-immunity-from-creatures)

<!-- markdown-toc end -->


# Components

## Balance Item +APR (cap +APR at 1/2 APR per item, replace w/ thac0 + dmg bonuses)

In an effort to balance out some mega-mod added items (some of the
older content) with insane boosts of things like +3 to +5 attacks per
round, this component normalizes all +APR items as such:

- 1 APR -> 1/2 APR, +1 thac0, +0 damage
- 1.5 to 2 APR -> 1/2 APR, +1 thac0, +1 damage
- 2.5 to 3 APR -> 1/2 APR, +2 thac0, +1 damage
- 3.5 to 4 APR -> 1/2 APR, +2 thac0, +2 damage
- 4.5 to 5 APR -> 1/2 APR, +3 thac0, +2 damage

The bonuses should apply to both the mainhand and offhand weapons.

Reasoning: the old APR, even used in offhand, provided a great
benefit to the mainhand, however I feel this also makes +APR items
extremely meta-game (using a +2 OH over a +4 or +5 OH, simply due to
the extra APR present on it).

Some other mods have a better balancing of +APR items, correlating a
small thac0 penalty alongside of it (attacking fast, but more
recklessly).  I like that idea, but needed a simple compensation for
the subtracted APR - another thought might be to keep some of the
crazy strength APR items from mods, but give a similar thac0 penalty
that is multiplied by the bonus (so a +3 APR item would incur a 6
thac0 penalty, a +5 APR item would incur a 10 thac0 penalty).

I feel my solution smoothes over the gear to keep overall team APR
numbers lower (as it's easier to totally overcome thac0 penalties
later on in game).

## Creatures

### Remove backstab immunity from creatures (not classes/items)

I've felt that it's a bit unfair to backstabbers that a lot of the
late game/tougher combat encounters totally nullified a class defining
feature for no good gameplay reason (RP wise, sure, it may make sense
you can't backstab a dragon - but maybe they have a weak
scale/achilles heel on their back?).

For a humanoid barbarian though, one of their class defining features
is the backstab immunity (likewise for a few rare items) - so this
should remain untouched.

### Remove timestop immunity from creatures

This has always seemed like a terrible game choice to me (although
perhaps exciting/surprising the first time it happens in ToB).
We aren't in JoJo's Bizarre Adventure though, so this component offers
the ability to remove this "immunity" (I would think of timestop as
"super speed", not a status ailment, so immunity being removed isn't
game breaking to me).

## Mods

Miscellaneous fixes or adjustments for third party mods (perhaps with
a focus on fixes to critical failures).

### Fix missing Oversight HQ door in Dark Horizons on EET

This component addresses the fact that DH does a hard copy of AR0700
(South Central BG), while EET will re-assign AR0700 to Waukeen's
Promenade, and flag South Central BG under BG0700.

The entrance can *still* be hard to find though, so see the
screenshot (I had to draw an arrow, the door cursor disappeared whenI
took the screenshot):

[oversighthq](https://github.com/ahungry/ahungry_tweaks/blob/master/oversighthq.png)
