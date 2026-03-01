# Terminal Interface Design Requirements

## Visual
- CRT terminal aesthetic: scanlines, phosphor glow, vignette, flicker, glass overlay
- CRT housing centered on a black background
- Screen is 40ch wide (matching in-game PI-40), 4:3 aspect ratio, centered on page
- Font loaded with display:block to prevent layout shift from fallback font
- One font size throughout — differentiation via colour and brightness only (no size variation)
- Phosphor green text, dim green for secondary, amber for labels/highlights
- Barrel distortion approximated via vignette and rounded corners

## Interaction
- Keyboard-only navigation — no mouse controls, no clickable links, no pointer cursor
- Arrow keys (and j/k) to move selection
- Enter to open
- Q/Escape to go back one level
- N/P and arrow left/right for next/prev document (forward/backward in time)
- Menu marker `>` moves in a fixed margin column — menu text stays in place and does not shift

## Content Rules
- Fully diegetic — no references to this being a game, no engine/Clojure references
- No unnecessary narrative or explanation — let the user's curiosity guide them
- No welcome messages or introductory text on the home page — just title and menu
- Post titles are concise (e.g. "Day 1: Silence" not "Recovered Field Log — Day 1")

## Structure
- Home page: centered title + minimal menu (Bulletin Board, Request Field Reference, Download Control Software)
- Bulletin Board: sub-page at /bulletins/ listing documents
- Documents: individual posts with scroll, next/prev navigation
- Q from document → bulletin board, Q from bulletin board → home

## Navigation Direction
- Documents are ordered oldest-first (chronological narrative)
- N (next) goes forward in time (older → newer)
- P (prev) goes backward in time (newer → older)
- Bulletin board lists documents oldest-first
