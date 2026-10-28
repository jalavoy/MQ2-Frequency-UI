# MQ2 Frequency UI

A custom EverQuest UI skin, with some windows extended for MacroQuest (MQ2).

It has been updated for the 10-21-2026 build of EverQuest.

This was based on the 2020 build by htw. I believe it was most recently posted
on the [MMOBugs Frequency UI page](https://www.mmobugs.com/forums/index.php?resources/frequency-ui.12/history).

Several windows (Buff, Short Duration Buff, Cast Spell, Group and Target) use
MQ2 `${...}` expressions. These only render properly with MacroQuest running.

## Installation

1. Copy the `Frequency` folder into your EverQuest `uifiles` directory, so you
   end up with `EverQuest/uifiles/Frequency/`.
2. In game, run `/loadskin Frequency`. You can also pick it from the UI skin
   option in the Options window.

## Non-update related changes

- Removed the "voice chat" indicators, since nobody uses this feature in-game.
- This was replaced with group threat indicators on your current target. 

## Credits and permissions

I believe the original Frequency UI was created by Frequency, 
and last updated by htw from mmobugs. I couldn't find a license 
for the original, so this repo doesn't add one. All credit for the build
I based this on goes to htw, and the stock EverQuest UI elements 
belong to Daybreak Game Company.

My updates are offered in the same spirit the original was shared. Feel free
to fork this and keep it going when future EverQuest patches break things.

If you're htw and would like this changed or taken down, please open an issue.

