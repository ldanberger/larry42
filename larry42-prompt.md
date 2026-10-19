Create a single self-contained HTML file (inline CSS, no JavaScript, Google Fonts allowed) for a links landing page titled "Larry42".

**Page**
- Engineering-paper background: a pale gray-green base (#e9eee9) with a fine 20px grid of faint green-gray lines and a stronger major line every 100px (every 5 squares), drawn with CSS gradients.
- Drafting tools drawn in inline SVG/CSS, fixed around the edges behind the content with soft drop shadows (decorative only, hidden from screen readers):
  - top left: a drafting compass (metal legs, needle point, pencil-lead leg, dashed arc it has drawn)
  - left middle: a 12-segment colour wheel (CSS conic gradient with a white centre and thin dividers)
  - bottom left: a cream slide rule with tick marks, 1–10 scale numbers and a clear sliding cursor with a red hairline
  - top right: a yellow HB pencil (pink eraser, silver band, sharpened wood tip) angled toward the content
  - right middle: a silver stopwatch (crown and side button, white face with 60 ticks, 15/30/45/60 labels, a small sub-dial) whose red second hand slowly sweeps once a minute
  - bottom right: a translucent blue protractor with degree ticks and 0–180 labels
  - Fade them on screens under 1100px wide, and on phones keep only the compass, slide rule and pencil, very faint.
- One centred column up to 560px wide, with a side gutter of at least 16px.
- Title "Larry42": very large and bold (Space Grotesk), with tight letter spacing and a blue-to-violet gradient (#1580c4 → #7a4fe0).
- Directly below the title, in small muted monospace text: larry.danberger@larryhere.com
- Add a keywords meta tag including Larry42, Larry Danberger, larry.danberger@larryhere.com and the site/game names.

**Links**
Show each link as a full-width card: the name on the left, a shortened web address in small monospace text on the right (hidden on phones under 420px wide), and an end icon. Use a 22px blank space between groups. In order:

1. Crossword: https://ldanberger.github.io/Crossword/
2. *(space)*
3. Chain Reaction: https://ldanberger.github.io/chainreaction/
4. Marble Maze: https://ldanberger.github.io/Maze/
5. Fox and Hounds: https://ldanberger.github.io/Fox/
6. Froggie: https://ldanberger.github.io/Froggie/
7. Dig Runner: https://ldanberger.github.io/Digrunner/
8. Mouse Maze: https://ldanberger.github.io/Mousemaze/
9. Life: https://ldanberger.github.io/Lifegrid/
10. Words: https://ldanberger.github.io/Words/
11. Forrest Tag: https://ldanberger.github.io/ForestVR/
12. *(space)*
13. Dycad: https://dycad.com
14. *(space)*
15. Larryhere: https://larryhere.com
16. *(space)*
17. AHRNow: https://ahrnow.com
18. TakeBackTheHeat: https://takebacktheheat.org

**Card styles by group**
- **Games, Crossword to Forrest Tag (playful):** each card has its own bright two-colour gradient (pink-orange, orange-yellow, purple-pink, green-lime, amber-coral, cyan-blue, red-violet, teal-cyan, green-mint, magenta-gold), plus a few semi-transparent white bubble dots. Use the Fredoka font in white with a slight text shadow, 18px rounded corners and a ▶ end icon. Give them a raised 3D button look (a solid darker shadow of the same colour below), lifting with a slight tilt on hover and pressing down when clicked.
- **Dycad (high-tech blue):** a deep navy-to-blue gradient with a fine cyan grid overlay, a glowing cyan border and outer glow, the JetBrains Mono font in pale cyan and a cyan → icon. A light sweep animates across the card every few seconds.
- **Larryhere (green business with high tech):** a dark green gradient with faint vertical lines and a soft green glow on the right, a solid 4px bright green bar on the left, a bold clean font in pale mint and a green → icon.
- **AHRNow and TakeBackTheHeat (antique):** aged parchment (cream to tan gradient, darker edges, subtle stains), a brown double-ruled border, the Cormorant Garamond serif font in dark brown with the web address in italics, small 6px corners and a ❧ end icon.

**Accessibility**
- Show a dark outline when a card is selected with the keyboard.
- Turn off all animations and hover movement when the visitor's system is set to reduce motion (prefers-reduced-motion).
- Links open in the same browser tab.
