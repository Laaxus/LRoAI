## Announcement

version 0.7.4 released.
This mod is updated to 1.5.10

## Description

This mod is based on the amazing work of Anbeeld. Unfortunately, he decided to stop supporting ARoAI (that you can find [here](https://github.com/Anbeeld/ARoAI)). I decided to continue his work.

The original mod description was : "**ARoAI** is a mod that focuses on making the AI in Victoria 3 as good as possible at developing economy and infrastructure of the countries controlled by it".

My goal is to completely rewrite it, step by step, to make it better and provide clear documentation so that the community can keep it going when I eventually step back.

## Current performance vs ai

![Roadmap](/img/lroai_comp_0.6.0.png)

Vanilla (1.5.9) vs LRoAI 0.7.2 (1.5.9)

## Current state of the mod
I believe that LRoAI is now feature complete.
What remains to be done is :

1) Around 50-100h of parameters tuning
2) Debugging (because I can't believe there's no bug)
3) Document the code for the modders
4) Add player autobuild back

## FAQ

### How can I contact you ?

If you have anything LRoAI to tell me about, the [Victoria 3 modding discord](https://discord.com/channels/827163966551621662/1161712336034332692) is the best place.
I usually answer within 24h.

### AI does not build anything from government construction ?

It can take time for the construction to start, up to a month.
If a country still does not build after 2 months (and does not have very small revenue like luxembourg), then contact me.

### What happened to the  ARoAI player autobuild feature ?

I removed it because I wanted the code to be as clean as possible, to make it easy to maintain and easy to understand for other modders.
I'll add it back later (probably after february 1st).

### A bunch of nations disbanded their armies down to almost nothing, is it intended ?

The intended behavior is that 25% of the revenue balance after fixed expense is going to military, and 75 into construction.
A few countries start with an army it can't support. Reducing the size of the army allows the country to actually industrialize.

### It seems you're not very active on the repository anymore ?

I'm in my last year of university and I have a thesis to write. I can't spend too much time on the mod for the current moment. I should hopefully be done with it by february 1st.

## Installation
#### Official release

I'll make it officially available on the steam workshop, paradox mods and paradox forum once 1.5 releases.

#### Manual installation

1) Download [the archive](https://github.com/Laaxus/LRoAI/releases) with the latest version.
2) Unpack it so you have a folder named "LRoAI" with mod's contents inside.
3) Go to "Documents > Paradox Interactive > Victoria 3 > mod" or create such a folder if it doesn't exist.
4) Place your "LRoAI" folder here.
5) Open launcher and add the mod to your playset or create a new playset with it if you don't have one.

It should look like this :

![files](/img/arborescence.png)

## Dev Diaries

- Dev Diary 0 : [A New Beginning](https://laaxus.github.io/2023-10-10-the-beginning/)
