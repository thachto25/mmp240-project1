---
version: alpha
name: "MMP240_Project 1"
description: "Change this to name your audience and describe how your design should feel to them."
omitted: [rounded]
colors:
  defaultText: "#0D2740"
  defaultBackground: "#D5EAFE"
  alternateText: "#204160"
  alternateBackground: "#F7FBFF"
  action: "#234D27"
  hover: "#122612"
  buttonText: "#F3FF7C"
typography:
  rootSize: 18px

fontFamilies:
  body: "Source Serif 4"
  headings: "Oswald"

sizes:
  body: 1rem
  small: 0.618rem
  h1: 4.236rem
  h2: 2.618rem
  h3: 1.618rem
  h4: 1rem
  h5: 0.618rem
  h6: 0.382rem

spacing:
  sm: 1.125rem
  md: 1.5rem
  lg: 3rem
  xl: 4.5rem
  xxl: 6rem
---

## Overview

Change this to name your audience and describe how your design should feel to them.

## Colors

Default colors apply to the page. Alternate colors apply to grouped sections. Links and buttons use the action color, then hover on pointer hover. Button text uses buttonText. Keep links underlined.

- Default Text on Default Background: 12.33:1 — meets the 4.5:1 target for normal text.
- Alternate Text on Alternate Background: 10.17:1 — meets the 4.5:1 target for normal text.
- Links and buttons on Default Background: 7.88:1 — meets the 4.5:1 target for normal text.
- Links and buttons on hover on Default Background: 12.98:1 — meets the 4.5:1 target for normal text.
- Button text: 8.97:1 — meets the 4.5:1 target for normal text.
- Button text on hover: 14.79:1 — meets the 4.5:1 target for normal text.

## Typography

The base font size is 18px. Use Source Serif 4 for body text and Oswald for headings. All size values use rem so changing the root size scales the full type system.

## Layout

Default line height is 1.6. Default page width is 960px. Use the spacing scale for gaps and padding: sm 1.125rem, md 1.5rem, lg 3rem, xl 4.5rem, xxl 6rem.

## Do and Don't

### Do

- Use the same exported `style.css` on every page so the type, colors, and spacing stay consistent.
- Use headings in order, beginning with one `h1`, then moving through lower heading levels as the content needs them.
- Keep underlined links and visible keyboard focus so people can find and use interactive content.

### Don't

- Create one-off colors, font sizes, or spacing values when an exported choice already fits the purpose.
- Rely on color alone to communicate meaning; use clear text, labels, or icons too.
- Change a design decision in only one file. Update the form and export a fresh set of files when the system changes.
