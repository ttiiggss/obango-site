# Tooltip System Guide

Your website now has beautiful, glassmorphic tooltips that appear on hover! Here's how to use and customize them.

## Current Tooltips

1. **"Jack of All Trades, Master of None"** - Shows the full proverb
2. **"semiotic principles"** - Explains what semiotics means
3. **"Nostr protocol"** - Describes the Nostr protocol

## How to Add More Tooltips

### Basic Tooltip
Wrap any text with this HTML:

```html
<span class="tooltip" data-tooltip="Your tooltip text here">Hoverable Text</span>
```

### Accent Tooltip (with special styling)
For emphasis, use the accent variant:

```html
<span class="tooltip tooltip-accent" data-tooltip="Your tooltip text here">Hoverable Text</span>
```

## Examples You Can Add

### In the About Section
```html
<span class="tooltip" data-tooltip="Building robust, scalable systems that handle real-world traffic.">network engineering</span>
```

### In the Values Section
```html
<span class="tooltip" data-tooltip="Versatility enables creative problem-solving across disciplines.">Depth over specialization</span>
```

### In Project Cards
```html
<span class="tooltip" data-tooltip="A peer-to-peer video conferencing platform.">hivetalk.org</span>
```

## Styling

The tooltips automatically match your site's aesthetic:
- **Glassmorphic background** with backdrop blur
- **Smooth animations** (fade in/out with subtle movement)
- **Accent color borders** for the special variant
- **Responsive** - they work on all screen sizes
- **Dotted underline** to indicate hoverable text

## Tips

- Keep tooltip text concise (1-2 sentences max)
- Use tooltips for technical terms, acronyms, or additional context
- Don't overuse - only add where it genuinely adds value
- The `tooltip-accent` class is great for quotes or special emphasis
