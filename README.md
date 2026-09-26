# Duel Decoder

A candidate-filter and optimal-guess suggestion tool for the Yu-Gi-Oh! Master Duel "Guess the Card" event. Ships with data for all 9,060 monster cards; progress is stored in your local browser only — no account, nothing uploaded.

English fork of [shangwen46-beep/yugioh-md-decoder](https://github.com/shangwen46-beep/yugioh-md-decoder).

## Features

- Record known clues (starting reveal + daily hints) and Right/Wrong feedback for each guess
- Automatically filters all candidate cards that match your constraints
- Information-entropy algorithm computes the best probe card for your next guess (Wordle-style strategy)
- Hints on when to spend a Hint
- Tracks remaining guess/hint counts
- Light/dark theme toggle

## Usage

Open the GitHub Pages link (see "Demo" below; if not enabled, turn it on under repo Settings → Pages). You can also download `index.html` and `cards.json` into the same folder and open `index.html` in a browser.

## Translation notes

- Card names were matched to official English names via MasterDuelMeta (by Konami passcode). Attribute/Race/Card Type values in `cards.json` are stored in English to match the UI.
- Card data fixes: `Black Luster Soldier` had id `5405695` upstream; corrected to the official passcode `5405694`.

## Disclaimer

This tool is a fan-made helper and is not affiliated with Konami / Master Duel. Card data may contain errors or be out of sync with the game version; treat suggestions as reference only and always trust the in-game display.

## License

Feel free to use, modify, and share.
