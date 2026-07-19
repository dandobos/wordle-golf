# Wordle Golf ⛳ Windmill Lane

Pass-and-play word golf for kids (1-4 players). 5 holes, each hole is a secret
5-letter word; guesses are strokes, lowest total wins. Every word comes with its
own gallery of themed critters who react to each guess and sell hints for +1 stroke.
Words rest for 14 days after being played (localStorage cooldown, LRU fallback if a
par-pool is exhausted). Bank: 52 words (12 par-3, 29 par-4, 11 par-5).

- `index.html` — the whole game (art is parametric inline SVG, no dependencies)
- `words.js` — generated valid-guess dictionary (from words-raw.txt + course answers)
- `design-mockups/` — the tabbed design-exploration pages that led to this build

Live: https://dandobos.github.io/wordle-golf/
