# Golden Axe III - Playable Enemies & Bosses

**Version 1.3**

Play as enemies and bosses in *Golden Axe III*, with configurable six-button controls and an enemy health display.

## Playable bosses and remaining issues

Playable bosses have been fixed as far as possible. **The game has been completed using one of the bosses**, but there is no guarantee that every boss or enemy will work perfectly throughout the game.

Boss palettes can still look wrong in places, and some other characters may show unusual colors when a boss is the player. These are visual issues and are not critical to gameplay.

## Features

- Play as enemies and bosses in single-player.
- Use their attacks and special moves, plus magic borrowed from the original heroes.
- Adjust ABC and XYZ button layouts in Options.
- Turn friendly fire off for two-player cooperative play in Options.
- Hold and release Magic to choose its power, with optional rebalanced bottle damage.
- See the enemy's portrait, name, and remaining health.
- Use the original player health, magic, and lives display.
- Versus keeps its original character selection.

## Download and installation

[Download the playable-enemies patch](Golden_Axe_III_PlayableEnemies.zip).

Apply `Golden_Axe_III_PlayableEnemies.ips` to your own copy of `Golden_Axe_III_(J)_[h1].bin`. Apply it to the original game, not an already patched version. This patch includes the six-button controls and enemy HUD.

The required original file is 1,048,576 bytes, with CRC32 `65F4D556` and SHA-1 `a602f49de6f006b9cd210049496098dc01a1ca10`. Other versions have not been tested. No game ROM is included.

Reopen the patched game and start fresh. Set your emulator's controller to six-button to use X, Y, Z, and Mode.

## Controls

- **Character selection:** Up/Down cycles through 11 enemy/boss forms; Left/Right returns to the original heroes. Bosses appear in the center with the selection marker on their right and the four heroes darkened. Press Start to confirm.
- **Original heroes:** X blocks, Y uses the round attack, and Z uses the unique move.
- **Enemies and bosses:** X blocks or evades where supported; Y and Z use character-specific special moves.
- **Enemy strength:** press C at character selection to choose Normal or Strong. Strong uses the highest native close-combat damage values; Eve has one damage set. Magic and projectiles retain their existing damage.
- **Magic:** hold A (the default Magic button), then release to choose a 1-, 3-, or 6-bottle cast. Two nearby players facing each other can hold longer for a combined 10-bottle cast, using bottles from both players.
- **Magic options:** MAGIC CHARGE can be turned OFF for the original automatic selection. MAGIC BALANCE defaults to NEW: 6 / 20 / 48 / 90 HP for 1 / 3 / 6 / 10 bottles. LEGACY keeps 6 / 16 / 32 / 56 HP; combining charged selection with LEGACY displays NOT RECOMMENDED.
- **Options:** change ABC/XYZ layouts or enable the original three-button combinations.
- **Friendly fire:** set FRIENDLY FIRE to OFF in Options to prevent partner hits and grabs in two-player cooperative play. ON keeps the original behavior; Versus is unaffected.
- **Level select:** press A+B+C together at character selection.
- **Clear-screen cheat:** hold Mode and press Start during gameplay or camp. Clears visible enemies and makes dwarfs release their remaining items. Not available in Versus.

## Playable enemies and bosses in action

Choose an enemy or boss on the character-select screen.

![Playable boss selection showing Damned Hellstrike II and Normal strength](screenshots/Playable_Boss_Selection.png)

Play as a boss with the original player health, magic, and lives display.

![Playable boss exploring a stage with the player HUD](screenshots/Playable_Boss_Gameplay.png)

![Playable boss fighting enemies, with the target's name and health displayed](screenshots/Playable_Boss_Combat.png)

## Changes in version 1.3

- Added charged magic selection, a flashing cast-cost preview, separate charge/balance options, and the combined 10-bottle cooperative cast.
- Improved boss selection: centered previews and lightning, a marker on the right, darkened heroes, and no duplicate hero entries in the enemy cycle.
- Fixed Dead Frame II's trailing sprite in gameplay, character selection, and map screens, preserving each form's original appearance.
- Reduced boss-player palette bookkeeping, improving crowded scenes and barrel-break performance. Brief slowdown and some palette approximations remain.

![Magic selection and balance options](screenshots/Magic_Options.png)

## Original controls-only edition

The earlier [six-button controls and enemy HUD edition](Golden_Axe_III_6Button_EnemyHUD_v1.0.zip) is also available without playable enemies or bosses.

![Enemy health display](screenshots/Enemy_HUD_Preview.png)

![Options](screenshots/Options_Preview.png)
