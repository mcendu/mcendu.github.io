---
tags:
  - mapping
  - osu!mania
---

Rhythm Choice
=============

In a rhythm game, a player is required to do a certain action at specific
times as dictated by the game. It is named so because the player can use
the song played as part of the game to gauge their timing; Without the
song, the game is pure nonsense.

While a piece of music is needed in rhythm games, the player also expects
a level that is timed to it and fits as perfectly as possible. In
_osu!mania_, the player reacts by pressing keys, so the expectation is
that the player feels like they are playing the music rather than hitting
random keystrokes.

But no &ndash; mapping is not as complex as you thought. All you need is
to break the music down into layers, choose one or more layers to map, and
arrange your patterns in the way that respects the music. This section
covers the first two steps of the process.

## Breaking the music down

Mapping starts with analysis of the music. Analysis means that you break
the music down into various layers &ndash; say synth lead and pad, drums,
vocals, and FX like disc scratching.

![[garden/analysis.osu][analysis.osu],00:30:941 - An
example of how a mapper breaks down a rhythm.](/images/analysis.jpg)
_[See the map here.][analysis.osu]_

The above map tells how [ginkiha's][ginkiha] song _Paved Garden_ looks
like when broken down. The first column is for the violin, the second for
the pad, followed by kicks, snare, hi-hat, (not visible in screenshot)
cymbals and FX in order. You don't need to make such a map in order to
analyze the rhythm; Most of the time, you are able to analyze it as the
song goes, rewinding and replaying when you can't fully catch what is
going on. It is also OK to interpret the song differently from the above
map.

## Choosing what to map

After analyzing, the next thing to do is to choose what layer to map. But
first, consider who is your audience. Are you going to introduce someone
who never ever played rhythm games before? Or are you making something
that satisfies those who want to have a real challenge? Here is a summary
of what audiences at a specific level expects:
<a id="difficulty"></a>

- Players at the level of **Easy** might have only played _osu!mania_
intermittently, perhaps even never at all, and can fail even the easiest
of things.

- At the level of **Normal** would player begin to understand how
_osu!mania_ works.

- You would expect a player to execute something fast, like a moderately
long 1/4 stream, at the level of **Hard**.

- **Insane**-level players deserve a real challenge.

Once you decided upon who is your audience, you would decide which layers
are appropriate for them. For Easy-level players, it is best to just
stick to the most simple and obvious sound in the music, like drums.
When mapping an Insane, you can use as many layers as you want, as long
as the resulting beatmap looks aesthetically good to you.

Unless major changes in rhythm has occured, like an anime song going into
the chorus section, you should stick to the set of layers you chose. If
you switch what layers you are mapping at a random, unexpected time, you
risk confusing modders wanting to know how your map works, or even
players not caring that much.

The amount of keys in _osu!mania_ are limited. When you use too much
layers, you would find yourself trying to fit everything into a limited
space, resulting in a map that is confusing and can lead to unacceptable
patterns like _vibro_, especially in lower keycounts like 4K.

Of course, just deleting a few columns from the above example won't make
a proper map for the audience you want to target. Such a map puts all
rhythm played by an instrument into a single column, a style that few
players would appreciate. Modders would treat your work as a hitsound
template, and would urge you to make a proper map if you have nothing
else. Further more, doing maps this style easily violates the ranking
criterion regarding columns:

> **No column can be left empty.** If you want to use fewer keys, change
> the number of keys in the Song Setup.

To make a proper map, we need to arrange the notes in a playable and
appreciatable fashion. This will be covered by the next article about
composition.

[ginkiha]: https://osu.ppy.sh/beatmaps/artists/72
[analysis.osu]: /mania_guide/beatmaps/garden/analysis.osu
