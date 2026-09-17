# Contributing

Cases are welcome. The bar exists because a prompt library is judged by what its prompts produce, not by how many files it has.

## What a case has to be

| ✅ Accepted | ❌ Rejected |
|---|---|
| A **stated camera** — shot size, movement, height | "cinematic angles" |
| A **stated light** — time of day, direction, quality | "good lighting" |
| **One action beat** that fits the duration | three things happening in five seconds |
| A **configuration the model serves** — `480p`/`720p`, 4–30s, an aspect ratio valid for the mode | 1080p, 45s, `4:3` on image-to-video |
| A **sound cue** when `generate_audio` is on | audio on, nothing said about sound |
| A **reference note** on image-to-video cases: what the image must contain | "use a photo" |
| **60–90 words**, one paragraph, English | a 400-word specification |
| No brands, real people or copyrighted characters | "a Nike ad starring Messi" |
| Nothing a platform's ad review would refuse | injuries, gore, sexual content |

There is no minimum length and no penalty for a short prompt that does one job perfectly. There is a penalty for a prompt that is short because the constraints were left out.

## Layout a case must follow

```
content/seedance-atlas/cases/<slug>.json       ← the source of truth (add this file)
```

The repository files under `cases/<nnn>-<slug>/` are **generated** — `node scripts/publish-seedance-atlas.mjs` builds them from the site's content. Do not open a pull request against them directly; add the JSON case to the site repository instead (or paste it into an issue and a maintainer will add it).

The case schema:

```json
{
  "slug": "short-kebab-case-name",
  "category": "cinematic",
  "scene": "text-to-video",
  "title": { "en": "Two to five words" },
  "summary": { "en": "One line, under 110 characters: what the shot is." },
  "keywords": ["three", "to", "five", "search phrases"],
  "config": { "resolution": "720p", "duration": "5", "aspect_ratio": "16:9", "generate_audio": true },
  "prompt": "One paragraph, 60–90 words, English, no line breaks.",
  "why": { "en": "Two or three sentences on why the prompt is built the way it is." }
}
```

Add `"reference_note": { "en": "What the reference image must contain." }` when — and only when — `scene` is `image-to-video`, and use `"aspect_ratio": "adaptive"` there (the only ratio image-to-video accepts).

Validation runs on every build and a violation fails it: unknown category, unknown scene, an unpriced resolution, a duration outside 4–30, an aspect ratio the mode does not offer, a prompt under 40 or over 800 characters, a multi-line prompt, a non-ASCII character, a missing reference note on an image-to-video case, or a banned brand/real-person term. The credit figure is not yours to write — the build computes it with the pricing engine the API bills with.

## Style

Write for someone who will **edit** the prompt. Concrete nouns, one camera, one light, one beat. Avoid "8k", "masterpiece", "trending on artstation" and the rest of the quality-token folklore: they are not observable instructions and they crowd out the words that are.
