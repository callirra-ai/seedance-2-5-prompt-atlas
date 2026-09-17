<div align="center">

# Seedance 2.5 Prompt Atlas

**122 short, copy-ready prompts for Seedance 2.5 — each one shipped with the exact settings it was written for and the price the generator charges to run it.**

<img src="https://img.shields.io/badge/model-seedance--2.5-1f9c6b?style=flat-square" alt="model: seedance 2.5">
<img src="https://img.shields.io/badge/prompts-122-0969da?style=flat-square" alt="prompts: 122">
<img src="https://img.shields.io/badge/categories-12-8250df?style=flat-square" alt="categories: 12">
<img src="https://img.shields.io/badge/text--to--video-84-555555?style=flat-square" alt="text to video">
<img src="https://img.shields.io/badge/image--to--video-38-555555?style=flat-square" alt="image to video">
<img src="https://img.shields.io/badge/licence-CC%20BY%204.0-bf8700?style=flat-square" alt="licence: CC BY 4.0">
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs welcome">

<sub><a href="#what-this-is">What this is</a> · <a href="#the-rules-every-prompt-here-follows">The rules</a> · <a href="#the-prompts">The prompts</a> · <a href="#how-to-use-a-case">How to use</a> · <a href="#repository-layout">Layout</a></sub>

**[▶ Try any prompt — it opens the generator with everything already filled in](https://callirra.com/seedance-prompt-library?utm_source=github&utm_medium=atlas)**

<sub>122 deep links, one per prompt. Each one fills the form; none of them submits it.</sub>

</div>

---

## What this is

A prompt library for video, written the way a shot list is written: **camera, action, light, sound** — the four things a video model actually needs — and nothing else. Every prompt here is 60–90 words. That is a deliberate ceiling, not an accident of effort.

Long prompts feel safer and mostly are not. A prompt you cannot finish reading is a prompt you cannot edit, and editing is the whole job: the model will render *something* for any of these, and the difference between a usable clip and a wasted generation is whether you changed the subject, the location and the light before you pressed generate.

Every case is one folder with the prompt, the settings as JSON, and a README explaining what the shot is and why it is built that way.

| | |
|---|---|
| **Prompts** | 122, across 12 categories |
| **Length** | 60–90 words each, one paragraph, English |
| **Modes** | text → video (84) and image → video (38) |
| **Tiers** | `480p` and `720p`; 4–30 seconds — the only tiers Seedance 2.5 exposes here |
| **Audio** | 83 of 122 prompts carry a sound cue (`generate_audio`) |
| **Credits** | the live price for that exact configuration, computed with the same engine the site bills with |
| **Licence** | CC BY 4.0 — copy, adapt, ship commercially, no permission needed |

### What is verified, and what is not

Worth being precise about, because a prompt repository is easy to inflate:

- **Verified:** every configuration is validated at build time against the model's real capability table (resolution, duration range, aspect ratios per mode, reference limits), and every credit figure is computed by the pricing engine the API charges with. A case that quotes a setting the model cannot serve fails the build and never ships.
- **Not claimed:** these are not a gallery of rendered clips. There is no `output.mp4` here, because none of these was generated for this repository — they are recipes, priced and validated, not a showreel. If you want to see finished clips made with this model, the [showcase](https://callirra.com/seedance-showcase) is the place for that.

---

## The rules every prompt here follows

1. **One paragraph, 60–90 words.** Readable in one breath, editable in one pass.
2. **State the camera.** "Handheld low behind the shoulder", "locked wide from the waterline" — the model cannot guess a shot size.
3. **State the light.** Time of day, direction, quality. Lighting is the single highest-leverage sentence in a video prompt.
4. **Say what happens, physically.** One action beat per shot. Two beats in five seconds reads as a glitch.
5. **Sound is part of the shot.** 83 of these name what you should hear, because Seedance 2.5 generates audio and a silent clip of a rain scene is half a scene. The ones marked `silent` are silent on purpose.
6. **No brands, no real people, no copyrighted characters.** Not a legal footnote — a named brand is a thing the model renders badly and a thing you cannot use.
7. **Nothing that cannot be shown.** No injuries, no gore, nothing that a platform's ad review would refuse. The action is real, the harm is not.

---

## The prompts

### Cinematic & film scenes <sub>· 11 prompts</sub>

<sub>Single-shot film language: chase beats, quiet character moments, one-take walk-and-talks. The searches here are 'cinematic AI video prompt', 'movie scene prompt', 'film look'.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 001 | **[Bridge Pursuit Headlights](https://callirra.com/seedance-prompt-library/bridge-pursuit-headlights)**<br><sub>A telephoto pursuit in 21:9: a coupe weaves across a dusk bridge while the lens pans with the traffic.</sub> | text → video | `720p` · 5s · `21:9` · audio | 195 |
| 002 | **[Edit Suite Screen Glow](https://callirra.com/seedance-prompt-library/edit-suite-screen-glow)**<br><sub>A five-second pull-back in a dark edit suite, lit only by a flickering monitor and a red standby lamp.</sub> | text → video | `480p` · 5s · `16:9` · audio | 87 |
| 003 | **[Midnight Diner Encounter](https://callirra.com/seedance-prompt-library/midnight-diner-encounter)**<br><sub>A diner photo extended into a slow lateral dolly: one glance, two cups, steam in tungsten light.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 004 | **[Neon Rain Alley Chase](https://callirra.com/seedance-prompt-library/neon-rain-alley-chase)**<br><sub>A courier sprints through a rain-soaked neon alley, camera low and close, one unbroken take.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 005 | **[One-Take Corridor Walk](https://callirra.com/seedance-prompt-library/one-take-corridor-walk)**<br><sub>One unbroken gimbal take: two colleagues walk a hotel corridor while the camera leads them backward.</sub> | text → video | `720p` · 10s · `21:9` · audio | 389 |
| 006 | **[Platform Farewell Train](https://callirra.com/seedance-prompt-library/platform-farewell-train)**<br><sub>A station photo sent into motion: the lens racks focus from a raised hand to train windows sliding past.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 007 | **[Pre-Dawn Kitchen Letter](https://callirra.com/seedance-prompt-library/pre-dawn-kitchen-letter)**<br><sub>A quiet pre-dawn beat: one slow push-in on a woman reading a single page under a warm bulb.</sub> | text → video | `480p` · 5s · `16:9` · silent | 87 |
| 008 | **[Rehearsal Mirror Turn](https://callirra.com/seedance-prompt-library/rehearsal-mirror-turn)**<br><sub>An eight-second rehearsal beat: a handheld half-circle reveals the mirror and doubles the actor mid-line.</sub> | text → video | `720p` · 8s · `16:9` · audio | 311 |
| 009 | **[Service Tunnel Sprint](https://callirra.com/seedance-prompt-library/service-tunnel-sprint)**<br><sub>An eight-second tunnel sprint: a trolley camera retreats at knee height as a train headlight floods in.</sub> | text → video | `720p` · 8s · `16:9` · audio | 311 |
| 010 | **[Stairwell Heist Standoff](https://callirra.com/seedance-prompt-library/stairwell-heist-standoff)**<br><sub>A heist beat held in one tilt: a hooded figure freezes on a stairwell landing as a torch beam climbs.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 011 | **[Tailor Measuring Hands](https://callirra.com/seedance-prompt-library/tailor-measuring-hands)**<br><sub>A tailor-shop photo animated with one slow arc: tape along a shoulder, chalk on wool, soft window light.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |

### Product & commercial <sub>· 11 prompts</sub>

<sub>Ads that sell: food, drinks, cosmetics, tech, fashion. Built for drops, hero spots, and social cutdowns — 'product video ad prompt', 'commercial B-roll'.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 012 | **[Burger Sizzle and Flame](https://callirra.com/seedance-prompt-library/burger-sizzle-flame-grill)**<br><sub>A patty searing on a flat-top, steam cut by a hard hood light, one rise from plate to flame.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 013 | **[Chilled Soda Can Crack-Open](https://callirra.com/seedance-prompt-library/chilled-orange-soda-crack-open)**<br><sub>Your can photo comes alive: the ring pull lifts, mist escapes, one slow arc keeps the label readable.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 014 | **[Chocolate Unwrap and Snap](https://callirra.com/seedance-prompt-library/chocolate-unwrap-snap-beat)**<br><sub>Eight seconds of foil, snap and crumb: a warm low-key unwrap that keeps the wrapper facing the lens.</sub> | image → video | `720p` · 8s · `adaptive` · audio | 311 |
| 015 | **[Coffee Pour Hero Shot](https://callirra.com/seedance-prompt-library/coffee-pour-hero-shot)**<br><sub>Your product photo, turned into a five-second hero shot: a slow pour, rising steam, one clean camera push.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 016 | **[Earbud Case Hinge Macro](https://callirra.com/seedance-prompt-library/earbud-case-hinge-macro)**<br><sub>An unbranded charging case opens under one sweeping highlight, probed at macro scale for eight seconds.</sub> | image → video | `720p` · 8s · `adaptive` · silent | 311 |
| 017 | **[Face Serum Drop Reveal](https://callirra.com/seedance-prompt-library/face-serum-drop-reveal)**<br><sub>A serum drop falls onto skin under shadowless light while the bottle label stays perfectly readable.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 018 | **[Iced Tea Pour Over Ice](https://callirra.com/seedance-prompt-library/iced-tea-pour-over-ice)**<br><sub>Iced tea over ice in morning window light, one pull-back that keeps the label legible throughout.</sub> | image → video | `480p` · 5s · `adaptive` · audio | 87 |
| 019 | **[Perfume Bottle Light Sweep](https://callirra.com/seedance-prompt-library/perfume-bottle-light-sweep)**<br><sub>A faceted perfume bottle on wet black stone, caustics thrown across the surface, one slider reveal.</sub> | text → video | `480p` · 5s · `9:16` · silent | 87 |
| 020 | **[Silk Scarf Fall, Fashion](https://callirra.com/seedance-prompt-library/silk-scarf-fall-fashion)**<br><sub>A silk scarf falls in slow motion through striped golden-hour light, tracked down to the floor.</sub> | text → video | `720p` · 5s · `3:4` · silent | 195 |
| 021 | **[Skincare Before and After](https://callirra.com/seedance-prompt-library/skincare-before-after-glow)**<br><sub>A ten-second vertical before-and-after: the same skin, one light sweep, no claims and no text.</sub> | text → video | `720p` · 10s · `9:16` · silent | 389 |
| 022 | **[Sneaker Spin Reveal, Studio](https://callirra.com/seedance-prompt-library/sneaker-spin-reveal-studio)**<br><sub>A floating unbranded sneaker turns on a dark studio gradient, rim-lit so every material reads.</sub> | text → video | `720p` · 5s · `1:1` · silent | 195 |

### Anime & stylised motion <sub>· 10 prompts</sub>

<sub>2D and cel-shaded motion: sakuga cuts, manga panels coming alive, ink and watercolour. Big with Japanese, Korean, Chinese and Southeast Asian audiences.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 023 | **[Cel-Shaded Sword Draw](https://callirra.com/seedance-prompt-library/cel-shaded-sword-draw)**<br><sub>One draw, one three-frame smear: a masked duelist clears her blade as the background erupts into speed lines.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 024 | **[Cel-Shaded Turn To Camera](https://callirra.com/seedance-prompt-library/cel-shaded-turn-to-camera)**<br><sub>Your character sheet, turned to camera: she holds the design, then finds the lens.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 025 | **[Chibi Teahouse Slip](https://callirra.com/seedance-prompt-library/chibi-teahouse-slip)**<br><sub>A chibi cook saves a stack of bowls with one foot, in flat colours and heavy squash.</sub> | text → video | `480p` · 5s · `1:1` · silent | 87 |
| 026 | **[Magical Girl Transformation](https://callirra.com/seedance-prompt-library/magical-girl-transformation)**<br><sub>A transformation in one orbit and one hard cut: ribbon light, sparkles, a final landed pose.</sub> | text → video | `720p` · 8s · `9:16` · audio | 311 |
| 027 | **[Manga Panel Comes Alive](https://callirra.com/seedance-prompt-library/manga-panel-comes-alive)**<br><sub>A manga panel comes alive: the inked runner steps over the border into the next panel.</sub> | text → video | `720p` · 5s · `3:4` · silent | 195 |
| 028 | **[Mecha Hangar Launch](https://callirra.com/seedance-prompt-library/mecha-hangar-launch)**<br><sub>Your mecha sheet, launched: gantry steam, a hard drop, and a blue-flame climb out of the bay.</sub> | image → video | `720p` · 8s · `adaptive` · audio | 311 |
| 029 | **[Painted Market Street Continues](https://callirra.com/seedance-prompt-library/painted-market-continues)**<br><sub>Your painted frame kept alive: lanterns swing, steam turns, a cat crosses between the stalls.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 030 | **[Retro Sports Anime Serve](https://callirra.com/seedance-prompt-library/retro-sports-anime-serve)**<br><sub>Retro TV sports anime: a volleyball smash held on the impact frame, then a slow replay tilt.</sub> | text → video | `720p` · 5s · `4:3` · audio | 195 |
| 031 | **[Sumi-e Ink Dragon](https://callirra.com/seedance-prompt-library/sumi-e-ink-dragon)**<br><sub>Ink on blank paper gathers into a coiled dragon, stroke by stroke, in monochrome sumi-e.</sub> | text → video | `720p` · 5s · `21:9` · silent | 195 |
| 032 | **[Watercolour Train Commuter](https://callirra.com/seedance-prompt-library/watercolour-train-commuter)**<br><sub>A watercolour commuter watches the fields slide past until a tunnel swallows the light.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |

### Dance & music video <sub>· 10 prompts</sub>

<sub>Choreography, concert light, beat-synced cuts, street dance. The prompts that carry audio, because the beat is half the shot.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 033 | **[Ballet Barre Rehearsal](https://callirra.com/seedance-prompt-library/ballet-barre-rehearsal)**<br><sub>Your studio frame, kept: a barre balance unfolding into a slow arabesque in the mirror.</sub> | image → video | `480p` · 8s · `adaptive` · audio | 138 |
| 034 | **[Beat-Synced Garage Cuts](https://callirra.com/seedance-prompt-library/beat-synced-garage-cuts)**<br><sub>One dancer, one locked frame, a cut on every kick: jacket and angle change, body stays.</sub> | text → video | `720p` · 8s · `1:1` · audio | 311 |
| 035 | **[Concert Light Drop](https://callirra.com/seedance-prompt-library/concert-light-drop)**<br><sub>From the pit: lights slam on, the floor jumps, the camera pushes through to the rail.</sub> | text → video | `480p` · 5s · `21:9` · audio | 87 |
| 036 | **[Drummer Kit Close-Up](https://callirra.com/seedance-prompt-library/drummer-kit-close-up)**<br><sub>Your kit, kept: a fast tom fill, both wrists blurred, landing hard on the crash.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 037 | **[K-Pop Style Formation Hook](https://callirra.com/seedance-prompt-library/kpop-formation-hook)**<br><sub>Nine dancers, one formation change on the downbeat, in two locked camera setups.</sub> | text → video | `720p` · 10s · `16:9` · audio | 389 |
| 038 | **[Rain Street Cypher](https://callirra.com/seedance-prompt-library/rain-street-cypher)**<br><sub>A rain-soaked street cypher: handheld circle, splashing footwork, a freeze on the last bar.</sub> | text → video | `720p` · 8s · `16:9` · audio | 311 |
| 039 | **[Rooftop Sunset Groove](https://callirra.com/seedance-prompt-library/rooftop-sunset-groove)**<br><sub>One dancer on a rooftop at last light, low camera, then a crane to full silhouette.</sub> | text → video | `720p` · 8s · `9:16` · audio | 311 |
| 040 | **[Salt Flat Silhouette Duet](https://callirra.com/seedance-prompt-library/salt-flat-silhouette-duet)**<br><sub>Your photo kept: a slow contact duet on white salt, sun down the lens, long shadows.</sub> | image → video | `720p` · 10s · `adaptive` · silent | 389 |
| 041 | **[Singer Mid-Verse](https://callirra.com/seedance-prompt-library/singer-mid-verse)**<br><sub>A singer mid-verse, camera arcing profile to close-up, one hard backlight through haze.</sub> | text → video | `720p` · 8s · `9:16` · audio | 311 |
| 042 | **[Underwater Silk Duet](https://callirra.com/seedance-prompt-library/underwater-silk-duet)**<br><sub>Two dancers in silk, weightless and in unison, as the camera sinks from the surface.</sub> | text → video | `720p` · 10s · `9:16` · audio | 389 |

### Nature & landscapes <sub>· 10 prompts</sub>

<sub>Aerial coasts, storm light, deserts, aurora, time-lapse weather. Drone language and slow reveals for travel and wallpaper channels.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 043 | **[Aurora Over a Frozen Lake](https://callirra.com/seedance-prompt-library/aurora-frozen-lake-night)**<br><sub>A locked-off night shot: only the aurora moves above a frozen lake and a black spruce treeline.</sub> | text → video | `720p` · 8s · `16:9` · silent | 311 |
| 044 | **[Coastline Drone Pullback at Dawn](https://callirra.com/seedance-prompt-library/coastline-drone-pullback-dawn)**<br><sub>A drone skims the swell, then pulls back to reveal a whole bay of dark sea cliffs in first light.</sub> | text → video | `720p` · 8s · `21:9` · audio | 311 |
| 045 | **[Desert Dune Wind Sweep](https://callirra.com/seedance-prompt-library/dune-crest-wind-sweep)**<br><sub>Your dune photo comes alive as wind lifts a ribbon of sand off the crest and carries it along the ridge.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 046 | **[Fog Drifting Through Pine Forest](https://callirra.com/seedance-prompt-library/fog-drift-through-pines)**<br><sub>A slow walk through fog and pine trunks where depth is made entirely of layers of grey.</sub> | text → video | `480p` · 5s · `16:9` · silent | 87 |
| 047 | **[Glacier Calving in Wide Shot](https://callirra.com/seedance-prompt-library/glacier-calving-wide-angle)**<br><sub>A ten-second hold on an ice wall, then a slab shears off and the wave spreads across still water.</sub> | text → video | `720p` · 10s · `21:9` · audio | 389 |
| 048 | **[Jungle Waterfall in Full Flow](https://callirra.com/seedance-prompt-library/jungle-waterfall-vertical-flow)**<br><sub>A vertical climb beside a jungle waterfall, from the plunge pool up to the lip it pours over.</sub> | text → video | `720p` · 5s · `9:16` · audio | 195 |
| 049 | **[Lava Fountain at Dusk](https://callirra.com/seedance-prompt-library/lava-fountain-crater-dusk)**<br><sub>Molten rock pulses out of a crater at dusk while the camera arcs slowly around the rim.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 050 | **[Sunrise on the Mirror Salt Flat](https://callirra.com/seedance-prompt-library/mirror-salt-flat-sunrise)**<br><sub>A salt-flat photo with a thin film of water, doubled by the first colour of sunrise.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 051 | **[Storm Light Over Open Moorland](https://callirra.com/seedance-prompt-library/storm-light-over-moorland)**<br><sub>After the rain, the camera tilts down from a black cloud base to a shaft of sun crossing wet heather.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 052 | **[Terraced Rice Fields in Morning Mist](https://callirra.com/seedance-prompt-library/terraced-rice-fields-mist)**<br><sub>A terraced hillside photo, with mist lifting off the flooded paddies step by step at dawn.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |

### Animals & pets <sub>· 10 prompts</sub>

<sub>Pet portraits in motion, wildlife at speed, farm and aquarium life. The most-shared category on social, and the easiest to get wrong.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 053 | **[Aquarium Fish Behind Glass](https://callirra.com/seedance-prompt-library/aquarium-fish-drift-tank)**<br><sub>A planted tank in close-up: one shoal holding against the current, focus pulling through the glass.</sub> | text → video | `720p` · 5s · `16:9` · silent | 195 |
| 054 | **[Bee Working an Open Bloom](https://callirra.com/seedance-prompt-library/bee-working-open-bloom)**<br><sub>Macro vertical of a bee landing, circling the stamens and grooming in hard midday sun.</sub> | text → video | `720p` · 4s · `9:16` · audio | 156 |
| 055 | **[Cat Knocks a Mug Off the Table](https://callirra.com/seedance-prompt-library/cat-knocks-mug-off-table)**<br><sub>A photo of a cat beside a mug, extended into the slow paw push, the topple and the drop.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 056 | **[Elephant Taking a Dust Bath](https://callirra.com/seedance-prompt-library/elephant-dust-bath-dusk)**<br><sub>An elephant sprays dust over its own back in three slow sweeps while the camera rises with the cloud.</sub> | text → video | `720p` · 8s · `21:9` · audio | 311 |
| 057 | **[Flock Lifting Off the Water](https://callirra.com/seedance-prompt-library/flock-lifts-off-water)**<br><sub>A raft of small wading birds on a lagoon bursts into flight, the camera whipping up after them.</sub> | text → video | `480p` · 5s · `16:9` · audio | 87 |
| 058 | **[Fox Pouncing in Deep Snow](https://callirra.com/seedance-prompt-library/fox-pounce-in-snow)**<br><sub>A fox goes still, leaps nose-first into the snow and comes up with a mouthful of it.</sub> | text → video | `720p` · 8s · `16:9` · silent | 311 |
| 059 | **[Horse Galloping Across a Meadow](https://callirra.com/seedance-prompt-library/horse-gallop-across-meadow)**<br><sub>A horse runs flat out from left to right, tracked at speed with the sun directly behind it.</sub> | text → video | `720p` · 8s · `16:9` · silent | 311 |
| 060 | **[Hummingbird at the Feeder](https://callirra.com/seedance-prompt-library/hummingbird-feeder-hover)**<br><sub>A square four-second hold on a feeder: the bird arrives, sips twice, backs off and hovers.</sub> | text → video | `480p` · 4s · `1:1` · silent | 69 |
| 061 | **[Puppy's First Snow at the Doorway](https://callirra.com/seedance-prompt-library/puppy-first-snow-doorway)**<br><sub>A puppy photo stepped into the snow: one paw lifted, nose down, warm door light on blue snow.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 062 | **[Wet Dog Shake in Slow Motion](https://callirra.com/seedance-prompt-library/wet-dog-shake-slow-motion)**<br><sub>Your photo of a wet dog turned into the shake: one twist, a halo of water, droplets across the floor.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |

### Sports & action <sub>· 10 prompts</sub>

<sub>Football strikes, skate lines, surf barrels, boxing rounds, motorsport. Impact, sweat and slow motion done properly.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 063 | **[Gymnastics Floor Landing](https://callirra.com/seedance-prompt-library/gymnastics-floor-landing)**<br><sub>Your still of a gymnast mid-air, continued: the double twist lands and the finish holds a full beat.</sub> | image → video | `480p` · 5s · `adaptive` · silent | 87 |
| 064 | **[Harbour Fisheye Skate Line](https://callirra.com/seedance-prompt-library/harbour-fisheye-skate-line)**<br><sub>One fisheye follow-cam skate line: push, ollie, grind, pop out, held a metre off the tail.</sub> | text → video | `720p` · 8s · `4:3` · audio | 311 |
| 065 | **[Limestone Overhang Move](https://callirra.com/seedance-prompt-library/limestone-overhang-long-move)**<br><sub>A single long move on a limestone overhang, filmed straight down from a fixed rope.</sub> | text → video | `720p` · 5s · `9:16` · silent | 195 |
| 066 | **[Night Circuit Drift Lock](https://callirra.com/seedance-prompt-library/night-circuit-drift-lock)**<br><sub>A night-circuit drift, ten seconds from entry to exit, filmed by a camera planted on the tarmac.</sub> | text → video | `720p` · 10s · `16:9` · audio | 389 |
| 067 | **[Ring Corner Boxing Exchange](https://callirra.com/seedance-prompt-library/ring-corner-boxing-exchange)**<br><sub>One square-ring exchange: a hook on a raised guard, sweat in the air, the camera orbiting without a cut.</sub> | text → video | `720p` · 8s · `1:1` · audio | 311 |
| 068 | **[Rooftop Basketball Dunk](https://callirra.com/seedance-prompt-library/rooftop-basketball-dunk)**<br><sub>A vertical phone clip of a rooftop dunk, tilting from the sneakers to the rim in one golden-hour beat.</sub> | text → video | `720p` · 5s · `9:16` · audio | 195 |
| 069 | **[Snowboard Powder Spray](https://callirra.com/seedance-prompt-library/snowboard-powder-spray)**<br><sub>Your snowboard still, continued: one hard carve, a wall of powder, a chase camera sliding out.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 070 | **[Sprint Start From The Rail](https://callirra.com/seedance-prompt-library/sprint-start-rail-track)**<br><sub>The first three strides of a sprint final, tracked at ankle height from beside the lane.</sub> | text → video | `480p` · 5s · `21:9` · audio | 87 |
| 071 | **[Stadium Free Kick Strike](https://callirra.com/seedance-prompt-library/stadium-free-kick-strike)**<br><sub>A free kick shot from turf level: two frames of ball compression, then a whip right into the back of the net.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 072 | **[Surf Barrel Continuation](https://callirra.com/seedance-prompt-library/surf-barrel-continuation)**<br><sub>Your still of a surfer inside the barrel, continued: the lip throws, the tube closes behind him.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |

### VFX & sci-fi <sub>· 10 prompts</sub>

<sub>Mecha, portals, magic hands, city-scale destruction, transformations. VFX language that a video model can actually hold together.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 073 | **[Armour Plate Transformation](https://callirra.com/seedance-prompt-library/armour-plate-transformation)**<br><sub>Armour plates surfacing through a hoodie, locking segment by segment, under one cold work lamp.</sub> | text → video | `720p` · 5s · `9:16` · audio | 195 |
| 074 | **[Colony Ship Cloud Break](https://callirra.com/seedance-prompt-library/colony-ship-cloud-break)**<br><sub>A colony ship dropping through fog: ten seconds of downwash, floodlights and one slow tilt.</sub> | text → video | `720p` · 10s · `21:9` · audio | 389 |
| 075 | **[Desert Portal Opening](https://callirra.com/seedance-prompt-library/desert-portal-opening)**<br><sub>Your half-formed portal still, continued: the ring closes, sand lifts off the ground, the tarp snaps flat.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 076 | **[Downtown Collapse Shockwave](https://callirra.com/seedance-prompt-library/downtown-collapse-shockwave)**<br><sub>Your collapsing block, continued: the shockwave crosses, glass bursts outward, the drone retreats.</sub> | image → video | `480p` · 5s · `adaptive` · silent | 87 |
| 077 | **[Floating Hologram Console](https://callirra.com/seedance-prompt-library/floating-hologram-console)**<br><sub>A holographic panel unfolding from a wristband, its light spilling onto real objects on the desk.</sub> | text → video | `720p` · 5s · `3:4` · silent | 195 |
| 078 | **[Frozen Instant Crossing](https://callirra.com/seedance-prompt-library/frozen-instant-crossing)**<br><sub>Your street still, continued: everything stops mid-motion and the camera drifts through the freeze.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 079 | **[Hangar Mecha Launch](https://callirra.com/seedance-prompt-library/hangar-mecha-launch)**<br><sub>A mecha launch from inside the hangar: pilot clamped in, cradle rising, the doors parting ahead.</sub> | text → video | `720p` · 8s · `16:9` · audio | 311 |
| 080 | **[Hex Shield Impact](https://callirra.com/seedance-prompt-library/hex-shield-impact)**<br><sub>An energy shield in three states: thin lattice, hardened plate, fading ripple, with the recoil landing.</sub> | text → video | `720p` · 5s · `1:1` · audio | 195 |
| 081 | **[Rain Street Magic Casting](https://callirra.com/seedance-prompt-library/rain-street-magic-casting)**<br><sub>Magic over a rain puddle: water beads lift, gather into a ring of ice, then fall back as rain.</sub> | text → video | `720p` · 5s · `9:16` · audio | 195 |
| 082 | **[Warehouse Gravity Flip](https://callirra.com/seedance-prompt-library/warehouse-gravity-flip)**<br><sub>A warehouse gravity flip: a dropped wrench reverses mid-fall and the camera rolls a half turn with it.</sub> | text → video | `720p` · 8s · `16:9` · silent | 311 |

### Historical & fantasy <sub>· 10 prompts</sub>

<sub>Period detail, wuxia wirework, mythology, castles and courts. Popular across Chinese, Middle Eastern and European searches alike.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 083 | **[Bamboo Grove Wirework](https://callirra.com/seedance-prompt-library/bamboo-grove-wirework)**<br><sub>Two swordswomen trade one mid-air pass between bamboo trunks as the camera rises with them.</sub> | text → video | `720p` · 5s · `9:16` · audio | 195 |
| 084 | **[The Candlelit Library](https://callirra.com/seedance-prompt-library/candlelit-ancient-library)**<br><sub>A scholar turns a paper volume toward a candle, dust drifting through the beam.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 085 | **[Desert Caravan Crossing](https://callirra.com/seedance-prompt-library/desert-caravan-crossing)**<br><sub>Twelve camels cross a dune ridge at late afternoon as the camera pulls back into the empty erg.</sub> | text → video | `720p` · 5s · `21:9` · silent | 195 |
| 086 | **[Dragon Above the Peaks](https://callirra.com/seedance-prompt-library/dragon-above-the-peaks)**<br><sub>A dragon glides between snow peaks and the camera pulls back to the whole range.</sub> | text → video | `720p` · 5s · `21:9` · audio | 195 |
| 087 | **[Knight at the Gate](https://callirra.com/seedance-prompt-library/knight-arrival-courtyard)**<br><sub>A lone knight rides through a castle gate at first light, from shadow into sun, in one low wide shot.</sub> | text → video | `720p` · 5s · `16:9` · silent | 195 |
| 088 | **[Lantern Street Procession](https://callirra.com/seedance-prompt-library/lantern-street-procession)**<br><sub>A Tang-era lantern street at dusk: one carried lantern against a crowd of a hundred, in one rising move.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 089 | **[Longship in the Fog](https://callirra.com/seedance-prompt-library/longship-in-the-fog)**<br><sub>A longship pushes through flat fog, oars biting together, in a reference-locked image-to-video shot.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 090 | **[Mughal Court Procession](https://callirra.com/seedance-prompt-library/mughal-court-procession)**<br><sub>A court procession crosses red sandstone toward a marble pavilion in one rising symmetrical move.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 091 | **[Duel in the Rain](https://callirra.com/seedance-prompt-library/samurai-duel-in-rain)**<br><sub>Two figures face off in steady rain, one sheathed blade and one held breath, in a slow push-in.</sub> | text → video | `480p` · 5s · `16:9` · audio | 87 |
| 092 | **[Siege at Dawn](https://callirra.com/seedance-prompt-library/siege-at-dawn)**<br><sub>Defenders work the wall walk as a distant engine arm swings and dust blooms at the gate.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |

### City & street <sub>· 10 prompts</sub>

<sub>Neon rain, commuter rush, rooftop reveals, market mornings. The everyday city as a character — vlog and B-roll workhorse.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 093 | **[Cafe Window Rain Zoom](https://callirra.com/seedance-prompt-library/cafe-window-rain-zoom)**<br><sub>A slow zoom into a rain-streaked cafe window until the wet street outside becomes abstract colour.</sub> | text → video | `480p` · 5s · `16:9` · audio | 87 |
| 094 | **[Crosswalk Commuter Rush](https://callirra.com/seedance-prompt-library/crosswalk-commuter-rush)**<br><sub>A jib drops into the morning rush: commuters cross on long parallel shadows under hard early sun.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 095 | **[Fire Escape Descent](https://callirra.com/seedance-prompt-library/fire-escape-descent)**<br><sub>A vertical five seconds from above: hands and shoes sweep past the lens on an iron fire escape at dusk.</sub> | text → video | `720p` · 5s · `9:16` · audio | 195 |
| 096 | **[Laundromat Night Wait](https://callirra.com/seedance-prompt-library/laundromat-night-wait)**<br><sub>A laundromat photo held still: drums turn, a page turns, green fluorescents against one orange glow.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 097 | **[Market Morning Steam](https://callirra.com/seedance-prompt-library/market-morning-steam)**<br><sub>A market photo sent into motion: hands bag produce, steam rolls, and the camera weaves up the aisle.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |
| 098 | **[Mist Bridge Cyclist Dawn](https://callirra.com/seedance-prompt-library/mist-bridge-cyclist-dawn)**<br><sub>A parallel tracking shot in 21:9: a cyclist crosses a misted bridge at dawn, piers fading into white.</sub> | text → video | `720p` · 5s · `21:9` · audio | 195 |
| 099 | **[Night Bus Window Seat](https://callirra.com/seedance-prompt-library/night-bus-window-seat)**<br><sub>An eight-second aisle creep on a night bus, faces lit in amber pulses by passing street lamps.</sub> | text → video | `720p` · 8s · `16:9` · audio | 311 |
| 100 | **[Plaza Pigeon Burst](https://callirra.com/seedance-prompt-library/plaza-pigeon-burst)**<br><sub>One whip pan catches a pigeon flock exploding off a plaza as a skateboarder rolls through the sun line.</sub> | text → video | `720p` · 5s · `4:3` · audio | 195 |
| 101 | **[Rooftop Sunrise City Reveal](https://callirra.com/seedance-prompt-library/rooftop-sunrise-city-reveal)**<br><sub>An eight-second crane rise at first light: rooftop, parapet, and a city below turning from blue to gold.</sub> | text → video | `720p` · 8s · `21:9` · audio | 311 |
| 102 | **[Street Food Griddle Glow](https://callirra.com/seedance-prompt-library/street-food-griddle-glow)**<br><sub>A night street-food photo animated: coals flare under skewers, then the tilt finds the vendor.</sub> | image → video | `720p` · 5s · `adaptive` · audio | 195 |

### Macro & ASMR <sub>· 10 prompts</sub>

<sub>Extreme close-ups and satisfying physics: honey, ink, ice, glass, sand, slime. Slow motion that stands on texture alone.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 103 | **[Caster Sugar Dust Fall](https://callirra.com/seedance-prompt-library/caster-sugar-dust-fall)**<br><sub>Fine sugar falls as a lit curtain through a slit of light, shot from below, with the dry hiss on.</sub> | text → video | `720p` · 5s · `9:16` · audio | 195 |
| 104 | **[Droplet Crown Splash](https://callirra.com/seedance-prompt-library/droplet-crown-splash)**<br><sub>A droplet throws a crown of water that shatters into hanging beads, side-lit against black.</sub> | text → video | `720p` · 5s · `4:3` · audio | 195 |
| 105 | **[Frosted Glass Bead Trails](https://callirra.com/seedance-prompt-library/frosted-glass-bead-trails)**<br><sub>Condensation beads swell, break and drag clean trails down a frosted tumbler in cold dawn light.</sub> | text → video | `480p` · 5s · `3:4` · silent | 87 |
| 106 | **[Glossy Slime Stretch and Snap](https://callirra.com/seedance-prompt-library/glossy-slime-stretch-snap)**<br><sub>A translucent slab stretches to a bubble window and snaps, lit from underneath by a gel light.</sub> | text → video | `720p` · 8s · `1:1` · audio | 311 |
| 107 | **[Honey Ribbon Drizzle](https://callirra.com/seedance-prompt-library/honey-drizzle-ribbon-macro)**<br><sub>Honey folds off a dipper in one unbroken ribbon, backlit to amber against black, in wide macro.</sub> | text → video | `720p` · 5s · `16:9` · audio | 195 |
| 108 | **[Honeycomb Wax Cell Close](https://callirra.com/seedance-prompt-library/honeycomb-wax-cell-close)**<br><sub>A wax comb glows from underneath as honey creeps down one cell wall, focus crawling cell to cell.</sub> | image → video | `720p` · 5s · `adaptive` · silent | 195 |
| 109 | **[Ice Block Fracture](https://callirra.com/seedance-prompt-library/ice-block-fracture-closeup)**<br><sub>One tap, one hairline crack, one punch-in at the exact moment a clear block of ice splits in two.</sub> | text → video | `720p` · 5s · `1:1` · audio | 195 |
| 110 | **[Ink Bloom in Still Water](https://callirra.com/seedance-prompt-library/ink-bloom-in-still-water)**<br><sub>Black ink blooms through still water in grey veils, lit by a single overhead shaft in wide 21:9.</sub> | text → video | `720p` · 8s · `21:9` · silent | 311 |
| 111 | **[Oil Droplet Emulsion, Dark Field](https://callirra.com/seedance-prompt-library/oil-droplet-emulsion-darkfield)**<br><sub>Two oil droplets merge in dark-field light while the lens pushes past into the emulsion behind.</sub> | image → video | `720p` · 8s · `adaptive` · silent | 311 |
| 112 | **[Sand Avalanche on a Dune](https://callirra.com/seedance-prompt-library/sand-avalanche-dune-crest)**<br><sub>A dune crest collapses in chasing sheets while the camera cranes out; harsh low sun on dust.</sub> | text → video | `720p` · 10s · `21:9` · audio | 389 |

### Story & dialogue <sub>· 10 prompts</sub>

<sub>Two characters, one beat of tension: an argument, a confession, a joke, a reunion. Written so the acting reads without a script.</sub>

| # | Prompt | Mode | Settings | Credits |
|---|---|---|---|---|
| 113 | **[Reunion at the Gate](https://callirra.com/seedance-prompt-library/airport-gate-reunion)**<br><sub>A name card no longer needed: a young woman drops her bag and runs the last ten metres.</sub> | text → video | `720p` · 8s · `16:9` · audio | 311 |
| 114 | **[Asking for Directions](https://callirra.com/seedance-prompt-library/asking-for-directions)**<br><sub>Two strangers point opposite ways down the same street and laugh about it.</sub> | text → video | `480p` · 5s · `9:16` · audio | 87 |
| 115 | **[The Regular's Order](https://callirra.com/seedance-prompt-library/barista-and-a-regular)**<br><sub>A barista writes the order before it is finished, then looks up at the regular.</sub> | text → video | `720p` · 5s · `3:4` · audio | 195 |
| 116 | **[The Half-Time Speech](https://callirra.com/seedance-prompt-library/coach-halftime-speech)**<br><sub>A coach at eye level and one nod: the moment before a player stands up.</sub> | text → video | `720p` · 10s · `16:9` · audio | 389 |
| 117 | **[Confession in the Car](https://callirra.com/seedance-prompt-library/confession-in-the-car)**<br><sub>Engine off, rain on the glass: a confession the driver cannot look at.</sub> | image → video | `720p` · 8s · `adaptive` · audio | 311 |
| 118 | **[Interview Gone Wrong](https://callirra.com/seedance-prompt-library/job-interview-gone-wrong)**<br><sub>A candidate hears her own answer land wrong and the interviewer's pen stops.</sub> | text → video | `720p` · 10s · `16:9` · audio | 389 |
| 119 | **[Argument at the Kitchen Table](https://callirra.com/seedance-prompt-library/kitchen-table-argument)**<br><sub>One stops chewing: a kitchen-table argument where the tell is a fork set down, not the words.</sub> | text → video | `720p` · 8s · `4:3` · audio | 311 |
| 120 | **[Teaching a Child to Cook](https://callirra.com/seedance-prompt-library/parent-teaching-child-to-cook)**<br><sub>A father lets go of the spoon, the child stirs too fast, and both freeze.</sub> | image → video | `720p` · 8s · `adaptive` · audio | 311 |
| 121 | **[Break-Up on the Roof](https://callirra.com/seedance-prompt-library/rooftop-breakup)**<br><sub>One step back at the roof edge: a break-up told by hands going into pockets.</sub> | image → video | `720p` · 8s · `adaptive` · audio | 311 |
| 122 | **[Siblings Over a Game](https://callirra.com/seedance-prompt-library/siblings-over-a-game)**<br><sub>A finger jabbed at the screen, then a cable pulled: two siblings, one quiet room.</sub> | text → video | `480p` · 8s · `16:9` · audio | 138 |

---

## How to use a case

```bash
git clone https://github.com/callirra-ai/seedance-2-5-prompt-atlas.git
cd seedance-2-5-prompt-atlas

# the prompt on its own, ready to pipe into any API call
cat cases/001-*/prompt.txt

# the same case with its settings, price and keywords
cat cases/001-*/case.json
```

Or read it on the site, where the fields are already filled in: **[Seedance 2.5 Prompt Library](https://callirra.com/seedance-prompt-library?utm_source=github&utm_medium=atlas)**.

**Adapting one.** Keep the structure — camera, action, light, sound — and replace the subject, the location and the light with yours. The structure is what makes the shot; the nouns are what make it yours. If you change the duration or the tier, check the settings table in that case's README: a 5-second prompt with two action beats will not survive being cut to 4.

---

## Repository layout

```
cases/<nnn>-<slug>/
  README.md      what the shot is, its settings, the prompt, and why it is built that way
  prompt.txt     the prompt and nothing else — pipe it straight into an API call
  case.json      the same case as data: settings, credits, keywords, site links
catalog.json     the whole library in one file: every case, every price
README.md        this file
CONTRIBUTING.md  what a case has to be before it is merged
LICENSE          CC BY 4.0
```

Numbers are positions, not priorities: they order the library by category, and a new case appended to a category takes the next free number. **Renaming a file or a slug breaks the deep link into the generator**, which is the one part of the layout that is load-bearing.

---

## Contributing

Prompts are welcome. The bar is in [CONTRIBUTING.md](CONTRIBUTING.md) and it is short: a case needs a real action beat, a stated camera, a stated light, a configuration the model can actually serve, and a one-line answer to "why does this work".

---

## Licence

Prompts and documentation: **CC BY 4.0** — use them commercially, adapt them, republish them; credit this atlas and say what you changed. Attribution is not required for a clip you generate from a prompt. See [LICENSE](LICENSE).

<sub>Maintained by <a href="https://callirra.com">Callirra</a>. The atlas is generated from the same content the site serves — see <code>docs/SEEDANCE_PROMPT_ATLAS.md</code> in the site repository.</sub>
