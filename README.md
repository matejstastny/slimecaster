<img src="./public/banner.png" style="width: 100%;" />

# Slimecaster

A top-down shooter made in GameMaker Studio 2. Survive waves of slimes and defeat the big slime boss to win.

## Gameplay

Enemies spawn in waves and home in on the player. Each wave spawns faster than the last. Survive long enough to defeat the boss slime, or get overrun!

### Screenshots

| Gameplay                                     | Game Over                                      | Victory                                    |
| -------------------------------------------- | ---------------------------------------------- | ------------------------------------------ |
| ![Gameplay](public/screenshots/gameplay.png) | ![Game Over](public/screenshots/game_over.png) | ![Victory](public/screenshots/victory.png) |

## Controls

| Input                  | Action                         |
| ---------------------- | ------------------------------ |
| `W A S D` / Arrow keys | Move                           |
| Left click (hold)      | Shoot (machine gun, uses ammo) |
| Right click            | Shoot (single shot)            |
| `X`                    | Reload (restores 10 ammo)      |
| `R`                    | Restart                        |

## Mechanics

- **Ammo** - The machine gun has a max of 20 rounds. Reload with `X` to restore 10.
- **Waves** - Enemies spawn at regular intervals, always at least 600 pixels away from the player. Wave interval decreases over time (minimum 10 frames).
- **Small slime** - 5 HP, moves toward the player.
- **Boss slime** - 200 HP. Defeating it triggers the victory screen.
- **Death** - Any enemy collision sends you to the game over screen.

## Built With

- [GameMaker Studio 2](https://gamemaker.io/) - IDE `v2024.8.1.171`, Runtime `v2024.8.1.218`
- Font: [Super Funky](https://www.fontspace.com/super-funky-font-f40163) by Nate Piekos
