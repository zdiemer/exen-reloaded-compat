# exen-reloaded compatibility

Every ExEn game in the corpus, booted headlessly by `tools/harness/compat.py` in the
exen-reloaded repository and scored from the frames it presents. Regenerate with
`python tools/harness/compat.py run --out <this repo>`.

## Summary

| Games | Playable | Renders | Black | Crashed | Incompatible |
|--:|--:|--:|--:|--:|--:|
| 47 | 47 | 0 | 0 | 0 | 0 |

### What the tiers mean

| Tier | Meaning |
|---|---|
| `playable` | Responds to input and reaches several distinct screens without the VM stopping |
| `renders` | Draws real screens, but the generic key script got no response |
| `black` | Frames were presented, but every sampled frame was one flat colour |
| `crashed` | The VM stopped after the game started (fatal error or uncaught exception) |
| `incompatible` | Never presented a frame |

The input test is a generic script (select, fire, directions). A `renders` game may be
fine and just need different keys; check its clip.

## Games

| Game | Tier | Screen | Cause | Shot |
|---|---|---|---|---|
| 007Ice-Racer | `playable` | 101x80 |  | [shot](shots/007Ice-Racer.png) · [clip](clips/007Ice-Racer.gif) |
| AgeOfEmpiresMobile | `playable` | 132x176 |  | [shot](shots/AgeOfEmpiresMobile.png) · [clip](clips/AgeOfEmpiresMobile.gif) |
| Arthur&LesPirates | `playable` | 101x80 |  | [shot](shots/Arthur-LesPirates.png) · [clip](clips/Arthur-LesPirates.gif) |
| BanjoKazooie | `playable` | 101x80 |  | [shot](shots/BanjoKazooie.png) · [clip](clips/BanjoKazooie.gif) |
| BombJack | `playable` | 101x80 |  | [shot](shots/BombJack.png) · [clip](clips/BombJack.gif) |
| BombSquad | `playable` | 132x176 |  | [shot](shots/BombSquad.png) · [clip](clips/BombSquad.gif) |
| Charmed | `playable` | 101x80 |  | [shot](shots/Charmed.png) · [clip](clips/Charmed.gif) |
| Crash Bandicoot | `playable` | 101x80 |  | [shot](shots/Crash-Bandicoot.png) · [clip](clips/Crash-Bandicoot.gif) |
| CrazyCobra2 | `playable` | 132x176 |  | [shot](shots/CrazyCobra2.png) · [clip](clips/CrazyCobra2.gif) |
| EagleSquadron | `playable` | 128x160 |  | [shot](shots/EagleSquadron.png) · [clip](clips/EagleSquadron.gif) |
| FighterPilotEvolved | `playable` | 132x176 |  | [shot](shots/FighterPilotEvolved.png) · [clip](clips/FighterPilotEvolved.gif) |
| Flynn | `playable` | 101x80 |  | [shot](shots/Flynn.png) · [clip](clips/Flynn.gif) |
| FootballFans | `playable` | 101x80 |  | [shot](shots/FootballFans.png) · [clip](clips/FootballFans.gif) |
| GhostHunter | `playable` | 112x112 |  | [shot](shots/GhostHunter.png) · [clip](clips/GhostHunter.gif) |
| IFPingPong | `playable` | 132x176 |  | [shot](shots/IFPingPong.png) · [clip](clips/IFPingPong.gif) |
| IFRacing | `playable` | 101x80 |  | [shot](shots/IFRacing.png) · [clip](clips/IFRacing.gif) |
| IFRacing2 | `playable` | 132x176 |  | [shot](shots/IFRacing2.png) · [clip](clips/IFRacing2.gif) |
| IFSkiExtreme | `playable` | 112x112 |  | [shot](shots/IFSkiExtreme.png) · [clip](clips/IFSkiExtreme.gif) |
| IFSkiJumping | `playable` | 112x112 |  | [shot](shots/IFSkiJumping.png) · [clip](clips/IFSkiJumping.gif) |
| IFSudoku | `playable` | 132x176 |  | [shot](shots/IFSudoku.png) · [clip](clips/IFSudoku.gif) |
| JungleRun | `playable` | 101x80 |  | [shot](shots/JungleRun.png) · [clip](clips/JungleRun.gif) |
| MalibuRide2 | `playable` | 101x80 |  | [shot](shots/MalibuRide2.png) · [clip](clips/MalibuRide2.gif) |
| MidtownMadness3 | `playable` | 132x176 |  | [shot](shots/MidtownMadness3.png) · [clip](clips/MidtownMadness3.gif) |
| MonkeyBusiness | `playable` | 132x176 |  | [shot](shots/MonkeyBusiness.png) · [clip](clips/MonkeyBusiness.gif) |
| MotoGp | `playable` | 132x176 |  | [shot](shots/MotoGp.png) · [clip](clips/MotoGp.gif) |
| MutantAlert | `playable` | 101x80 |  | [shot](shots/MutantAlert.png) · [clip](clips/MutantAlert.gif) |
| Panko | `playable` | 120x143 |  | [shot](shots/Panko.png) · [clip](clips/Panko.gif) |
| Pikubi | `playable` | 112x112 |  | [shot](shots/Pikubi.png) · [clip](clips/Pikubi.gif) |
| Pikubi2 | `playable` | 101x80 |  | [shot](shots/Pikubi2.png) · [clip](clips/Pikubi2.gif) |
| Reversi | `playable` | 101x80 |  | [shot](shots/Reversi.png) · [clip](clips/Reversi.gif) |
| SexyBreakerBikini | `playable` | 128x128 |  | [shot](shots/SexyBreakerBikini.png) · [clip](clips/SexyBreakerBikini.gif) |
| SexyManga | `playable` | 128x128 |  | [shot](shots/SexyManga.png) · [clip](clips/SexyManga.gif) |
| SexyVideoPoker | `playable` | 101x80 |  | [shot](shots/SexyVideoPoker.png) · [clip](clips/SexyVideoPoker.gif) |
| ShadoFighter | `playable` | 101x80 |  | [shot](shots/ShadoFighter.png) · [clip](clips/ShadoFighter.gif) |
| SouthPark | `playable` | 128x141 |  | [shot](shots/SouthPark.png) · [clip](clips/SouthPark.gif) |
| SphereMadness | `playable` | 112x112 |  | [shot](shots/SphereMadness.png) · [clip](clips/SphereMadness.gif) |
| SphereMadness2 | `playable` | 132x176 |  | [shot](shots/SphereMadness2.png) · [clip](clips/SphereMadness2.gif) |
| Spyro | `playable` | 132x176 |  | [shot](shots/Spyro.png) · [clip](clips/Spyro.gif) |
| StarWars3 | `playable` | 101x80 |  | [shot](shots/StarWars3.png) · [clip](clips/StarWars3.gif) |
| TheTerminator | `playable` | 101x80 |  | [shot](shots/TheTerminator.png) · [clip](clips/TheTerminator.gif) |
| TombRaider | `playable` | 101x80 |  | [shot](shots/TombRaider.png) · [clip](clips/TombRaider.gif) |
| TombRaider2 | `playable` | 101x80 |  | [shot](shots/TombRaider2.png) · [clip](clips/TombRaider2.gif) |
| TombRaider3 | `playable` | 101x80 |  | [shot](shots/TombRaider3.png) · [clip](clips/TombRaider3.gif) |
| TourDeFrance | `playable` | 132x176 |  | [shot](shots/TourDeFrance.png) · [clip](clips/TourDeFrance.gif) |
| Worms | `playable` | 128x128 |  | [shot](shots/Worms.png) · [clip](clips/Worms.gif) |
| XMasTales | `playable` | 101x80 |  | [shot](shots/XMasTales.png) · [clip](clips/XMasTales.gif) |
| ZooTycoon2 | `playable` | 101x80 |  | [shot](shots/ZooTycoon2.png) · [clip](clips/ZooTycoon2.gif) |
