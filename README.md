# Ragdoll Shooters

A physics ragdoll shooter that runs right in your browser — no install.

## ▶ [Play now](https://dashryerson-design.github.io/ragdoll-shooters/)

Every character is a fully simulated ragdoll: real muscles and joints, limping when shot in the leg, doubling over from gut shots, and full ragdoll deaths.

### Features
- 7 weapons (pistol, magnum, SMG, M4, shotgun, sniper, LMG), each with its own damage and wound style
- 3 maps: **Tester**, **Park** and **House**
- 5 modes vs AI bots: Free For All, Team Deathmatch, Zone Hold, 1v1 and Gun Game
- Per-limb damage, blood, dismemberment and pain reactions
- Keyboard + mouse or touch (iPad) controls, first-person view, cosmetic armour

### Controls (keyboard)
| Key | Action |
|---|---|
| WASD | Move |
| Shift | Run |
| Space | Jump / climb |
| Mouse | Look |
| Left click | Shoot |
| Right click (hold) | Aim |
| I | First / third person |
| F | Go limp |
| P | Menu (volume, sensitivity, bots, difficulty, loadout) |

### Online multiplayer
Pick **ONLINE** on the game mode screen, choose your loadout, then use the **server browser**:
- **Create server** — host a game with your chosen mode and map; it appears in everyone's list
- **Join** — pick any server from the list (you can join mid-match)
- **Quick match** — joins the fullest open server of your mode, or creates one
- The browser shows how many players are online right now. Up to 8 players per server.

No game server to run: every player connects to free public MQTT message brokers (EMQX and HiveMQ) over secure websockets, the same way a web page loads, so it works on almost any network. Players on the GitHub page and on the claude.ai version share the same lobby.
