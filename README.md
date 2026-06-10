Generates procedural abstract art as a fullscreen wallpaper. Every result is unique.

**[Open the app →](https://bert4422.github.io/procedural-art-generator/)**

---

## Install as an app

### iPhone / iPad
1. Open the link above in **Safari**
2. Tap the **Share** button at the bottom
3. Tap **Add to Home Screen**
4. Tap **Add**

### Android
1. Open the link above in **Chrome**
2. Tap the **three-dot menu** in the top right
3. Tap **Add to Home Screen** or **Install app**
4. Tap **Add**

### Desktop (Chrome / Edge)
1. Open the link above
2. Click the **install icon** in the address bar on the right
3. Click **Install**

Once installed it opens fullscreen with no browser UI, just like a native app.

---

## Buttons

| Button | What it does |
|---|---|
| **Tune** | Opens the Tune panel for fine controls |
| **Settings** | Opens the Settings panel to pick algorithm, palette, and complexity |
| **Invert** | Inverts all colours on screen |
| **Random** | Generates a new random piece |
| **Auto Save** | Pick a folder and every generation saves there automatically. Click again to stop. Desktop Chrome and Edge only. |
| **Save PNG** | Saves the current image |
| **◎** | Hides and shows all buttons |
| **← ‹ ○●○ › →** | Navigate generation history. ← → moves back and forward. ‹ › scrolls the history dots. |

---

## Settings panel

- **Family** — broad category of algorithms to pick from
- **Algorithm** — the specific generation method
- **Palette** — colour scheme
- **Complexity** — how detailed the result is, from 1 to 10
- **Symmetry** — mirror or radial symmetry applied on top
- **Orientation** — landscape or portrait canvas
- Any setting left on **Random** gets picked randomly each generation

---

## Tune panel

- **Seed** — type a number to reproduce an exact previous result. Leave blank for random.
- **Algorithm sliders** — fine controls that appear based on the current algorithm. Each algorithm has different options such as warp strength, frequency, damping, fold count, and feed/kill rates.
- **Colour Formula** — type a math expression to override how colours are mapped. Works on pixel-based algorithms.

### Colour formula variables
| Variable | Meaning |
|---|---|
| `x` | Horizontal position, 0 to 1 |
| `y` | Vertical position, 0 to 1 |
| `v` | The raw computed value, 0 to 1 |
| `s` | The seed number |

Math functions available: `sin cos tan sqrt abs pow log floor ceil PI`

### Colour formula examples
| Formula | Effect |
|---|---|
| `v` | No change (passthrough) |
| `sin(x*10)*cos(y*8)*0.5+0.5` | Ripple grid |
| `sqrt(pow(x-.5,2)+pow(y-.5,2))*2` | Radial rings from centre |
| `(sin(x*PI*6)+1)/2` | Vertical colour bands |
| `pow(v,0.3)` | Brightens shadows and pulls out detail |

---

## Algorithms

| Algorithm | Family |
|---|---|
| Strange Attractor | Abstract |
| Harmonograph | Abstract |
| Recursive Subdivision | Abstract |
| Fourier Curves | Abstract |
| Plasma Field | Psychedelic |
| Domain Warp | Psychedelic |
| Mandala | Psychedelic |
| Reaction-Diffusion | Psychedelic |
| Fractal IFS | Psychedelic |
| Flow Field | Organic |
| Space Colonization | Organic |

---

## Palettes

21 colour palettes across five groups: Psychedelic, Organic, Warm, Cool, and Minimal. The three Minimal palettes (Monochrome, Chalk, Obsidian) are only available when chosen manually and are excluded from random selection.
