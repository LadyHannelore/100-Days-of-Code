# 100-Day Project Roadmap

This is my menu, not a rigid contract: I’ll aim for a small, working version
each day and treat extra polish as a stretch goal. I estimate the risk score as
the chance I won’t finish that day’s MVP in one coding session, while allowing
time to learn as I go. **1** means very manageable; **10** means very likely to
run over. I’ve scoped down any idea originally rated above 8; the scores shown
are for my revised MVP.

## Scope changes

I narrowed these ideas because they had too many moving parts for a reliable
one-day MVP. Each keeps its main learning goal:

- **Days 25, 50, 75, 100:** I’ll showcase a small selection or a single feature
  instead of integrating every project from the phase.
- **Days 5, 13, 17:** I’ll build a small grid game, visual mixing toy, or
  path-based flock animation instead of a full tactical or physics simulation.
- **Days 29, 31, 33–34, 37, 39, 44, 46, 49:** I’ll use one image, a small local
  dataset, or a simpler 2D visualization rather than broad APIs or advanced
  media/rendering pipelines.
- **Days 51–52, 54–57, 59, 61–63, 65–66, 69, 72–73:** I’ll use small 2D,
  fixed-data, or approximate models rather than large-scale, full 3D, or
  text-corpus work.
- **Days 77–83, 87–90:** I’ll focus on one core mechanic or a small sample
  rather than a complete simulator, editor, or precision instrument.
- **Days 92–99:** I’ll implement one simple, testable capstone slice per day
  rather than a production-ready worldbuilding platform.

## Phase 1: The Ehrenfest Workshop & Royal Academy (Days 1–25)

*Theme: bookmaking, fantasy systems, and small creative tools.*

| Day | Project and my one-day MVP | Risk |
|---:|---|:---:|
| 1 | **Movable Type Page (complete)** — I rendered entered text as a parchment-style page with a border, randomized ink variation, and printing animations. [Project](https://github.com/LadyHannelore/Movable-Type-Page) · [Day 1 notes](days/day-01.md) | 3 |
| 2 | **Seven-Element Mana Chart (complete)** — I built a dependency-free web app that visualizes seven adjustable elemental affinities in an SVG radar chart. [Project](https://github.com/LadyHannelore/Seven-Element-Mana-Chart) · [Day 2 notes](days/day-02.md) | 5 |
| 3 | **Tea Party Timing Game (complete)** — I built a short, self-contained game with six randomly selected library mishaps, choices to handle them, and a five o'clock deadline. [Project](https://github.com/LadyHannelore/Tea-Party-Timing-Game) · [Day 3 notes](days/day-03.md) | 4 |
| 4 | **Library Schumil Reply Bot** — I will match a few keywords to prewritten, characterful replies; no LLM required. | 4 |
| 5 | **Ditter Board Prototype (scoped)** — I will move two pieces on a small grid and capture a marked tile. | 7 |
| 6 | **Trombe Cellular Automaton** — I will show seeds spreading across a grid and clear them myself. | 5 |
| 7 | **Gil Merchant Calculator** — I will convert between coin denominations and calculate a simple profit margin. | 3 |
| 8 | **Feystone Color Toy** — I will change a crystal's gradient with pointer position on a canvas. | 4 |
| 9 | **Duchy Ranking Chart** — I will reorder a sample list of duchies and redraw their ranking. | 5 |
| 10 | **Seasonal Clock** — I will show local time with a theme that changes by season or time of day. | 4 |
| 11 | **Noble-Speak Translator** — I will transform a few common phrases using a small phrase dictionary. | 3 |
| 12 | **Harspiel Synth** — I will play a handful of plucked notes using the browser's Web Audio API. | 6 |
| 13 | **Potion Cauldron Toy (scoped)** — I will stir colored particles around a canvas and display a simple mixing score. | 8 |
| 14 | **Reading Speedometer** — I will count words in pasted text and estimate reading time. | 3 |
| 15 | **Magic Circle Generator** — I will create a decorative SVG from a few text inputs and repeated shapes. | 5 |
| 16 | **Lecture Counter** — I will count chosen character names and keywords in text I provide. | 5 |
| 17 | **Ordonnanz Bird Animation (scoped)** — I will animate a small flock of birds following simple paths. | 7 |
| 18 | **Plant-Paper Workshop** — I will balance a few resources over a short sequence of turns. | 6 |
| 19 | **Noble Crest Builder** — I will combine a shield, two colors, and a selected emblem into an SVG. | 5 |
| 20 | **Highbeast Morph Toy** — I will switch between two simple SVG creature silhouettes with a transition. | 6 |
| 21 | **Recipe Scaler** — I will scale ingredient amounts by serving count and show a sample feedback score. | 3 |
| 22 | **Shrine Order Puzzle** — I will solve a short sequence puzzle to reveal a locally stored message. | 4 |
| 23 | **Noble Alliance Graph** — I will display a small hand-authored character network and highlight neighbors on click. | 7 |
| 24 | **Ex-Libris Bookplate** — I will generate a printable bookplate SVG with a name and decorative border. | 4 |
| 25 | **Library Dashboard (scoped)** — I will make one simple page linking to a few finished reading tools or project demos. | 5 |

## Phase 2: AniList & Anime Data Studio (Days 26–50)

*Theme: anime data, visualizations, and browser media experiments.*

| Day | Project and my one-day MVP | Risk |
|---:|---|:---:|
| 26 | **AniList Profile Fetcher** — I will fetch one public profile field and show a clear error if the request fails. | 6 |
| 27 | **Anime Genre Constellation** — I will turn a small local genre-count list into a star chart. | 5 |
| 28 | **Studio Treemap** — I will visualize a sample studio dataset as labeled rectangles. | 7 |
| 29 | **Shared Voice Actor Graph (scoped)** — I will use a local list of five shows and shared cast names to draw a small graph. | 6 |
| 30 | **Taste Difference Chart** — I will compare a few sample personal scores with sample community scores. | 5 |
| 31 | **Anime Palette Poster (scoped)** — I will extract a few dominant colors from an image I select and show swatches. | 7 |
| 32 | **Light Novel Title Generator** — I will generate silly titles from a small hand-written word list. | 4 |
| 33 | **Manga Speed-Line Filter (scoped)** — I will convert an uploaded image to grayscale and overlay simple radial lines. | 7 |
| 34 | **Audio Spectrum Visualizer (scoped)** — I will draw a basic frequency bar display for an audio track I select. | 8 |
| 35 | **Seasonal Release Heatmap** — I will display a small local sample of anime release years and seasons. | 5 |
| 36 | **Dialogue Box Engine** — I will show typewriter text, one character portrait, and two branching choices. | 7 |
| 37 | **Animation Frame Viewer (scoped)** — I will step through a supplied set of still frames and compare adjacent frames. | 6 |
| 38 | **Anime Recommender** — I will rank a few sample backlog entries by overlap in genre tags. | 6 |
| 39 | **3×3 Anime Grid (scoped)** — I will fill a 3×3 layout with images and captions I select. | 6 |
| 40 | **Gacha Probability Simulator** — I will simulate pulls at a fixed rate and compare observed results with expected odds. | 6 |
| 41 | **Subtitle Karaoke Styler** — I will convert a tiny sample subtitle into a styled `.ass` file. | 7 |
| 42 | **Tournament Bracket** — I will create an eight-entry bracket and pick winners. | 4 |
| 43 | **Binge-Watch Planner** — I will calculate episodes per day from episode count and a target date. | 3 |
| 44 | **Toon-Shaded Sphere (scoped)** — I will draw a 2D sphere with a few stepped light bands and an outline. | 6 |
| 45 | **Quote Card Generator** — I will place my text over a chosen background and export an image. | 5 |
| 46 | **Source-Material Tracker (scoped)** — I will show a hand-curated list of five adaptations with source links and notes. | 4 |
| 47 | **Guess the Release Year Quiz** — I will quiz myself using a small local list of shows and release years. | 4 |
| 48 | **AniList Status Badge** — I will generate a static SVG card from a small JSON input file. | 5 |
| 49 | **Composer Footprint (scoped)** — I will summarize manually entered credits for five shows in a simple chart. | 5 |
| 50 | **Anime Wrapped Dashboard (scoped)** — I will present a small local dataset in one page with two charts and a summary. | 6 |

## Phase 3: The Red Book & Mapmakers of Arda (Days 51–75)

*Theme: fantasy cartography, languages, calendars, and simulations.*

| Day | Project and my one-day MVP | Risk |
|---:|---|:---:|
| 51 | **Runic Transcriber (scoped)** — I will map a small set of English letters to decorative substitute glyphs. | 5 |
| 52 | **Procedural Map Sketch (scoped)** — I will generate a small grid map with randomized land, water, and a few labels. | 7 |
| 53 | **Doors of Durin Puzzle** — I will reveal a simple SVG door when I enter the passphrase. | 4 |
| 54 | **Fellowship Pathfinding (scoped)** — I will find a path across a small square grid around one moving obstacle. | 6 |
| 55 | **Beacon Signal Chain (scoped)** — I will show a fixed chain of beacons and toggle which ones can see the next. | 5 |
| 56 | **Genealogy Explorer (scoped)** — I will display a small hand-authored family tree with clickable people. | 6 |
| 57 | **Ring Inscription Effect (scoped)** — I will reveal glowing text on a 2D ring illustration as the pointer approaches. | 6 |
| 58 | **Shire Meal Planner** — I will show meal times and pick produce from a short seasonal list. | 3 |
| 59 | **Rohirrim Flocking (scoped)** — I will animate a small group of dots using simple flocking rules; skip combat physics. | 7 |
| 60 | **Place-Name Builder** — I will combine a few supplied word roots and show their component meanings. | 5 |
| 61 | **Fellowship Timeline Map (scoped)** — I will plot three character paths and a few shared event markers on a static map. | 6 |
| 62 | **Shire Calendar Converter (scoped)** — I will convert dates using a clearly documented simplified calendar mapping. | 6 |
| 63 | **Palantír Smoke Orb (scoped)** — I will animate translucent smoke-like shapes inside a 2D sphere. | 6 |
| 64 | **Entmoot Simulator** — I will run a small state machine where characters take turns before reaching a decision. | 5 |
| 65 | **Moria Map (scoped)** — I will generate a single grid dungeon with rooms, corridors, and one hazard marker. | 6 |
| 66 | **Dialogue Pattern Analyzer (scoped)** — I will count selected words in a short user-provided or public-domain sample and chart them. | 5 |
| 67 | **Two Trees Light Cycle** — I will blend two animated colors across a simple landscape scene. | 5 |
| 68 | **Hoard Value Estimator** — I will estimate total value from a coin count I enter and an assumed coin weight. | 3 |
| 69 | **Siege Outcome Calculator (scoped)** — I will compare attacker and defender counts with a few transparent random trials. | 6 |
| 70 | **Riddle Duel** — I will ask several riddles and check answers against accepted alternatives. | 4 |
| 71 | **Middle-earth Herbarium** — I will show four fictional plants with simple SVG illustrations and descriptions. | 5 |
| 72 | **Star Chart (scoped)** — I will plot a small fixed set of stars and rotate the view with a time slider. | 6 |
| 73 | **Ash Plume (scoped)** — I will animate particles drifting across a grid in a chosen wind direction. | 6 |
| 74 | **Ballad Meter Helper** — I will count syllables approximately and mark a rhyme scheme I enter. | 6 |
| 75 | **Third Age Atlas (scoped)** — I will make one illustrated static map with selectable locations and short popups. | 6 |

## Phase 4: The Chronicler's Engine (Days 76–100)

*Theme: history, cryptography, trade, and a small worldbuilding capstone.*

| Day | Project and my one-day MVP | Risk |
|---:|---|:---:|
| 76 | **Cipher Desk** — I will encrypt and decrypt text with Caesar and Vigenère ciphers. | 6 |
| 77 | **Rotor Cipher Toy (scoped)** — I will show one rotating substitution wheel and encode a message with it. | 6 |
| 78 | **Silk Road Trade Game (scoped)** — I will choose between three routes while comparing cost and risk for two goods. | 6 |
| 79 | **Heraldry Generator (scoped)** — I will create a shield SVG and prevent combinations that break a simple tincture rule. | 6 |
| 80 | **Focus Tree Viewer (scoped)** — I will display a small clickable prerequisite tree and export its nodes as JSON. | 7 |
| 81 | **Wind-Rose Navigator (scoped)** — I will plot a route and show a compass with a simple prevailing-wind indicator. | 6 |
| 82 | **Dynasty Generator (scoped)** — I will generate three generations of a small family with a few random traits. | 6 |
| 83 | **Trebuchet Calculator (scoped)** — I will estimate projectile range from adjustable launch speed and angle. | 5 |
| 84 | **Coinage Debasement Chart** — I will plot a small hand-entered dataset of coin purity over time. | 4 |
| 85 | **Scroll Fragment Helper** — I will suggest likely missing letters in a short fragment I enter, using letter frequencies. | 6 |
| 86 | **Siege Supply Calculator** — I will estimate how supplies change over a march using adjustable army and distance values. | 5 |
| 87 | **Lanchester Battle Resolver (scoped)** — I will plot one simplified square-law battle from two starting force sizes. | 6 |
| 88 | **Sundial Plotter (scoped)** — I will draw an illustrative sundial with hour lines for a selected latitude. | 7 |
| 89 | **Epidemic Curve (scoped)** — I will plot a basic SIR model with adjustable transmission and recovery rates. | 6 |
| 90 | **Province Map Painter (scoped)** — I will color and label five fixed SVG regions; skip generated borders and economy totals. | 6 |
| 91 | **Capstone Kickoff** — I will choose a theme, write a small feature list, and sketch one screen for the final project. | 4 |
| 92 | **Capstone Map Slice (scoped)** — I will display a static SVG map with selectable provinces and a terrain color key. | 6 |
| 93 | **Capstone Timeline Slice (scoped)** — I will use a slider to switch among three prewritten era snapshots. | 5 |
| 94 | **Capstone Character Panel (scoped)** — I will show a few character cards with links to their locations on the map. | 6 |
| 95 | **Capstone Resource Tick (scoped)** — I will update one resource total across three regions when a turn button is pressed. | 6 |
| 96 | **Capstone Decision Event (scoped)** — I will add one two-choice event that changes a visible value. | 5 |
| 97 | **Capstone Chronicle Generator (scoped)** — I will turn three selected events into a formatted text chronicle. | 5 |
| 98 | **Capstone Visual Polish (scoped)** — I will add a consistent color palette, responsive spacing, and one subtle CSS effect. | 4 |
| 99 | **Capstone Save/Export (scoped)** — I will export the current project state as JSON and load it back. | 6 |
| 100 | **100-Day Museum (scoped)** — I will publish a gallery page for a handful of finished projects and link the capstone demo. | 5 |

## Daily log

I’ll create entries in `days/day-XX.md` from
[my daily notes template](DAY_TEMPLATE.md) and update progress in the
[README](README.md) as I complete days.
