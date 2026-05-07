# Apu Codex Pet

Apu is a custom animated pet for Codex. It is a soft, toy-like companion with a cream yellow hat, a blue bow, bright blue overalls, a yellow shirt, round shoes, and gentle pink cheeks. The character is designed to feel friendly at small UI sizes while still having a clear silhouette and expressive animation states.

![Apu contact sheet](assets/contact-sheet.png)

## Character

Apu is calm, curious, and quietly energetic. It is meant to feel like a small coding buddy rather than a noisy notification mascot: idle while you think, running while work is in progress, waving when it greets you, and briefly disappointed when something fails before getting ready to try again.

The visual language uses:

- A white rounded face for readable expressions.
- Blue overalls and shoes for a stable identity color.
- Yellow clothing for warmth and optimism.
- A tiny chest badge to suggest a Codex workspace companion.
- Short limbs and soft proportions so each animation reads well in a compact corner UI.

## Install

Copy the packaged pet into your Codex pets directory:

```bash
mkdir -p ~/.codex/pets/apu
cp pet/pet.json pet/spritesheet.webp ~/.codex/pets/apu/
```

Then select the custom pet named `小阿噗` in Codex. You may need to refresh Codex or reopen the pet panel if it is already running.

## Package

- Atlas: `8 x 9`
- Frame size: `192 x 208`
- Spritesheet: `1536 x 1872`
- Format: `WEBP`
- Mode: `RGBA`
- QA: passed with no validation errors or warnings

## License

Released under the MIT License.
