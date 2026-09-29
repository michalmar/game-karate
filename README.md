# Karate Legends: Path of the Dragon

A dependency-free browser fighting game built with HTML, CSS, Canvas, and vanilla JavaScript.

## Play

Open `index.html` in a modern browser, or serve the folder locally:

```bash
python3 -m http.server 8080
```

Then visit <http://localhost:8080>.

## Hosting

The game is deployed to Azure Static Web Apps through
`.github/workflows/azure-static-web-apps.yml`. Pushes to the deployment branch
publish the root directory directly because the game has no build step.

## Included

- Adaptive single-player AI based on the player's win rate
- Local two-player keyboard battles
- Endless survival mode
- Six unlockable arenas
- Arena-scaled rewards from 25 SP in Sakura Dojo to 150 SP in Dragon Sanctuary
- Persistent Skill Points, belts, record, and key bindings
- Belt-specific colors, combat abilities, and map bonuses
- Hit-stop, impact particles, damage callouts, and distinct block feedback
- Keyboard, touch, and standard Xbox/PlayStation Gamepad API controls