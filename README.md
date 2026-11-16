# Hello Swap

A mod for **Hello Neighbor** (Steam) with the roles swapped everywhere. **Grown-up Nicky** (the adult from Act 3) is in
the Neighbor's place: he guards the house, chases you, catches you and plays the Neighbor's part in every cutscene, up
to the giant in Act 4. And **you are the Neighbor**: in first person, as the kid, the teen and the adult in the
cutscenes, and as the small kid you save in the finale.

<!-- video / screenshots here -->

## What's in it
- Grown-up Nicky as the Neighbor, everywhere the game shows the Neighbor: AI, chase, catch, activities, cutscenes, Act 4
- You play as the Neighbor at his real height, with his body and shadow
- Swapped voices: Nicky makes Nicky's sounds, your breaths and screams are the Neighbor's
- Third person on F4 (first person again by itself in cutscenes, the catch and hiding spots)
- All acts and the finale; the Thing in Act 4 stays as it is

## Install
1. Download `HelloSwap-1.0.0.zip` from [Releases](../../releases) and unzip it anywhere (keep the folder until you uninstall).
2. Close Hello Neighbor and double-click **`Install.bat`**. It finds the game through Steam, or asks for its folder.
3. Start Hello Neighbor from Steam as usual and play any act.

The installer adds [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (the mod loader) unless you already have it, and the mod.
No game file is changed. **Uninstall:** double-click `Uninstall.bat`. It removes the mod, and also UE4SS if this
installer put it there.

## Keys
| Key | What it does |
|---|---|
| F4 | third person on / off |
| F8 | the mod's helpers on / off (the swapped models and voices stay) |

The rest are the game's own keys.

## Known limits
- The faces do not move (no blinking or lip motion).
- In the Act 1 and Act 2 cutscenes where you are a kid, the Neighbor is the kid's size.
- Grown-up Nicky has only a few voice lines in the game, so some of his sounds repeat.

## Trouble?
- Mods that also change the Neighbor or the player (Hello Nicky, Hello Playtime, Tom & Jerry, ...) fight with this one: use one at a time.
- Logs: `<Hello Neighbor>\HelloNeighbor\Binaries\Win64\swap_lua.log` and `ue4ss\UE4SS.log` in the same folder. Please attach both to an issue.
- A game update can break UE4SS mods. Tested with the Steam version of November 2026.

## Credits
- Made by **Gaming with ACK**.
- Everything you see and hear is Hello Neighbor's own content: the pak holds the game's own characters put on each other's skeletons and the game's own voice recordings swapped between them.
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT).
- Built with the help of an AI coding agent (Claude Code, Anthropic).

The mod's code is under the MIT licence. Unofficial fan mod, not affiliated with or endorsed by tinyBuild or Dynamic Pixels.
