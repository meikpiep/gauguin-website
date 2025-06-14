---
title: 'Monochrome theme for Gauguin'
description: "A new monochrome theme has been added to Gauguin."
date: 2025-06-14
image: /posts/2025/2025-06-14-v0-42-monochrome-theme/screenshot-monochrome-theme.png
---

There is a new version [0.42.0](https://github.com/meikpiep/gauguin/releases/tag/v0.42.0) of gauguin adding a monochrome theme.

The new version will be available via [F-Droid](https://f-droid.org/packages/org.piepmeyer.gauguin/) and [Google Play](https://play.google.com/store/apps/details?id=org.piepmeyer.gauguin) in a few days.

![Close-up with unfocused background of a vibrant large blue butterfly gracefully perched on a delicate flower amidst lush green gras](screenshot-monochrome-theme.png 'Main screen with monochrome theme'){decoding="sync" eleventy:widths="400"}

## Why a monochrome theme?

Gauguin uses vibrant colors in its UI by default. I was asking myself, if a monochrome theme may come up with a more 'zen-like' game play, reducing to the core of solving grids without distractions.

The monochrome theme is a kind of experiment, I tested it to fit my taste with the focus on the main screen. I then realized that may be the whole game should reflect the theme, so it is now a full-fledged theme in _some_ way. This still isn't a complete, solution, but I assume it good enough to let you test it if you want.

## Drawbacks

Currently, there are two major drawbacks:

1. To signal mistakes regarding the grid, the regular themes use variants of red. This does not comply with a monochrome theme, but so long, I did not figure out a good alternative.
2. The rest of the UI like the new game screen lacks contrast. The underlying Material UI uses colors to distinguish regions. Using color values without any saturation, the contrast of regions using different colors like primary and secondary lack differentiation.

## Feedback

If you have any ideas regarding the theme, reach out via [discussions](https://github.com/meikpiep/gauguin/discussions/315) or raise an [issue](https://github.com/meikpiep/gauguin/issues)