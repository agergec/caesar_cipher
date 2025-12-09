# Caesar Cipher Web Samples

Two self-contained HTML demos to teach and visualize the Caesar cipher (with Turkish alphabet support and multilingual UI).

- `caesar.html`: bar-style visualizer with parallel plain/cipher rows, slider/key buttons, and text I/O.
- `caesar_dial.html`: circular “cipher disk” view showing plain/cipher rings and a synced slider/key selector.

## Features
- Languages: Turkish, English, French (UI labels, sample text, accordion info, and Wikipedia link update per language).
- Alphabets: switches to the proper alphabet for the selected language (Turkish-specific letters included).
- Mode toggle: Encrypt / Decrypt with live recalculation.
- Key selection: click a letter tile or use the slider; visuals stay aligned in both modes.
- Case handling: preserves original letter case (Turkish casing rules respected).
- Accordion: brief Caesar cipher explanation + localized Wikipedia link.

## Usage
1. Open `caesar.html` or `caesar_dial.html` directly in your browser (no build step; all assets inline).
2. Pick a language from the dropdown.
3. Choose a key via the letter tiles or slider.
4. Type in the input box; the result updates live. Switch Encrypt/Decrypt to see both directions.

## Notes
- Both files are static and safe to serve from any static host or open via `file://`.
- The dial view fixes the top alignment marker to the chosen key while text uses the inverse shift in decrypt mode.
