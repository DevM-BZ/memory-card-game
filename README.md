# Memory Card Game

Interactive browser-based memory match built for the Option A student starter. The app fetches SVG card metadata from `data/card_info.json`, duplicates the set to form pairs, shuffles it, and renders a responsive flip animation so players can find every match before the tries counter hits zero.

## Technologies
- HTML5 for the layout and overlay structure
- CSS3 for the flip animations, overlays, and win celebration visuals
- Vanilla ES6 JavaScript for game state, DOM construction, and event handling

## Challenge Highlight
Implementing `dealCards` was the biggest lift: wiring up dynamic DOM creation with a `DocumentFragment`, attaching click handlers, and ensuring every card carried its dataset metadata correctly so the rest of the game logic could function without relying on hard-coded markup.
