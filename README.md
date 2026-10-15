# animate.svg

A personal collection of animated SVG assets for interfaces, loading states, feedback, buttons, and visual effects. The examples use SVG-native animation (SMIL) so they can be previewed directly in a browser and embedded as images in many contexts.

## Categories

### Buttons
- [Green/black animated arrow button](./buttons/green-black-arrow.svg)

### Loaders
- [Gradient spinner](./loaders/spinner.svg)
- [Pulsing dots](./loaders/pulse-dots.svg)

### Arrows and navigation
- [Sliding chevron arrows](./arrows/chevron-slide.svg)

### Status and feedback
- [Success check](./status/success-check.svg)
- [Error cross](./status/error-cross.svg)

### Progress
- [Indeterminate gradient progress bar](./progress/gradient-bar.svg)

### Effects
- [Floating gradient orb](./effects/gradient-orb.svg)

### Icons
- [Beating heart](./icons/heart-beat.svg)

### Backgrounds
- [Animated grid wave](./backgrounds/grid-wave.svg)

## Embedding

Use an SVG as an image:

```html
<img src="https://raw.githubusercontent.com/suissa/animate.svg/main/loaders/spinner.svg" alt="Loading">
```

For inline styling and interaction, copy the SVG markup into your HTML. Animation support can vary across SVG viewers and sanitizers; test the target environment before shipping.

## Contributing

Add new SVGs to the most relevant category, give each asset a descriptive filename, and include accessible `<title>` text. Prefer self-contained SVGs with no external dependencies.
