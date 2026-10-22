# Dathanna

Swipe to find colours that pass WCAG AA.

Dathanna deals you random colours one card at a time. Every colour passes AA text contrast (4.5:1) against white or black. Swipe right to keep a colour and left to veto it. Kept colours go into a library you can search and use to build a tested theme.

**[Open Dathanna](https://nuadyr.github.io/Dathanna/)**

## Screenshots

### Theme Builder (desktop)

<img src="docs/screenshots/desktop-theme-builder.png" alt="The Theme Builder on desktop. A list of passing contrast checks sits beside a grid of 15 CSS variables and a live preview of a sample web page." width="100%">

### Explorer (tablet)

<img src="docs/screenshots/tablet-explorer.png" alt="The explorer on a tablet-sized screen. A Dark Violet card shows its hex and RGBA codes and a 4.68 to 1 AA pass badge. Beside it, a live preview shows headings, a card and buttons in that colour on white. Veto, Undo and Keep buttons sit below." width="100%">

### Library (mobile)

<img src="docs/screenshots/mobile-library.png" alt="The Library tab on a phone showing 14 kept colours as swatches in a three column grid on white, with the black strip starting below." width="320">

## Features

- Keep or veto with a swipe, the buttons, or the arrow keys.
- Test colours against a white or a black backdrop.
- Every card shows the closest colour name, hex code, RGBA code and contrast ratio.
- Search your library by colour name or hex code, and copy it as CSS.
- Build a theme from 15 CSS variables, check contrast as you go, and copy it as CSS.
- Light, dark or automatic theme, and a button to pause motion.

## Run it

Dathanna is one HTML file with no build step and no dependencies. Open `index.html` in a browser.

## Privacy

Your library and settings stay in your browser. Colour names come from a built-in list. If you turn on "Look up colour names online", the colour's hex code and your IP address are sent to [api.color.pizza](https://api.color.pizza). It is off by default.

## Author

Dathanna is by [Nuadyr](https://nuadyr.github.io/). © 2026.
