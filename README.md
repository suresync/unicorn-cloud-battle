# Unicorn Cloud Battle

A cozy **parent vs kid** browser game for ages 6+. Two little unicorns battle on colorful cloud pads, then the winner spins a prize wheel for diamonds.

## How to open

**Easiest:** double-click `index.html` (or open it in Chrome / Safari / Firefox).

Or serve locally:

```bash
cd unicorn-cloud-battle
npx --yes serve .
```

Then open the URL shown in the terminal (usually `http://localhost:3000`).

No install required. Works offline after the page has loaded once (Google Fonts need a network connection the first time; the game still works without them).

## How to play

1. Enter two names (defaults: **Parent** and **Kid**).
2. Pick unicorn colors.
3. Press **Start Battle!**
4. Each round, both players secretly pick one move, then actions resolve together.
5. First to knock out all **3 hearts** wins.
6. Winner **spins the wheel** for diamonds. Play again anytime!

### Controls

| Action | Player 1 (left) | Player 2 (right) |
|--------|-----------------|------------------|
| Move left | **A** | **←** |
| Move right | **D** | **→** |
| Sparkle attack | **W** | **↑** |
| Shield | **S** | **↓** |
| Jump (dodge) | **Q** | **/** |

Big on-screen buttons work too — great for younger kids.

### Combat tips

- **Sparkle** hits if you are on the **same cloud** or a **neighbor** cloud.
- **Shield** blocks a sparkle.
- **Jump** dodges a sparkle.
- If nobody attacks, you just hop around the clouds — still fun!

## Gameplay summary

Simultaneous-choice arena on 5 colored cloud pads. Short rounds, hearts for HP, yay-style banners, an ambient unicorn trotting across the sky, and a diamond prize wheel after each match.

## License

Made for family play. Use and share freely.
