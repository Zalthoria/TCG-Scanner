# ðŸƒ TCG Scanner

A mobile-first web app that uses your phone camera to automatically identify Trading Card Game cards and build your collection â€” powered by Claude Vision AI.

## Features

- ðŸ“· **Live camera scanning** â€” Point your phone at any card
- ðŸ¤– **AI auto-detection** â€” Claude Vision identifies the card every 5 seconds
- ðŸ’° **Price estimates** â€” Estimated market value (USD, Near Mint)
- ðŸ“¦ **Collection storage** â€” Cards saved locally in your browser
- ðŸƒ **Multi-game support** â€” PokÃ©mon TCG, Magic: The Gathering, Yu-Gi-Oh!, Digimon, and more

## Usage

1. Open the app on your phone browser
2. Tap **Scan Card** to open the camera
3. Align a card within the guide frame
4. Claude auto-identifies it every 5 seconds, or tap **Scan Now**
5. Tap **+ Add to Collection** to save it
6. View your collection on the home screen

## Tips

- Lay cards flat on a plain dark surface
- Good lighting is key â€” avoid glare on holo cards
- For holo/foil cards, angle slightly to reduce reflection

## Tech

- Vanilla HTML/CSS/JS â€” no frameworks, no build step
- [Anthropic Claude API](https://docs.anthropic.com) for vision-based card identification
- `localStorage` for persistent collection storage
- Hosted on GitHub Pages

## Disclaimer

Price estimates are AI-generated from training data and may not reflect live market rates. Always verify on [TCGPlayer](https://tcgplayer.com), [Cardmarket](https://cardmarket.com), or eBay before buying or selling.
