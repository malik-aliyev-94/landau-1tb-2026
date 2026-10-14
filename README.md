# Code Heroes — Ayan’s School Adventure

Open **code-heroes-ayan.html** in Chrome, Edge, Firefox, or Safari. The HTML includes its cartoon artwork and all game code. It works offline and needs no installation or companion files.

This update uses the original Ayan-photo game as its source. Ayan is the only child character. The 21 fictional classmates, character roster, rescue counts, and hero-unlocking system have been removed. BEEP and Mr. Glitch remain as non-child story characters.

Play three missions: fix the school’s colors, move BEEP to the power star, and answer 12 profession questions. Move BEEP with the arrow keys, W/A/S/D, or the on-screen buttons. Movement is immediate. Wrong answers allow another try; correct quiz answers show a short explanation before you choose Next Question. There is no timer. Play Again restarts the adventure.

Jobs: firefighter, veterinarian, gardener, doctor, teacher, chef, builder, pilot, dentist, mechanic, artist, and software developer.

The raw portrait is not included in the delivered HTML. The embedded character is generated cartoon art based on the supplied Ayan portrait. A separate copy is provided as **ayan-cartoon.png**. The images **code-heroes-preview.png** and **code-heroes-quiz-preview.png** show the opening and quiz screens.

## Checks

Tested in Chrome with networking disabled: full adventure, all 12 quiz questions, wrong-answer retries, correct-answer explanations, color updates, robot wall and rock collisions, immediate keyboard and on-screen movement, robot reset, finale, and replay. No script errors or network requests. Desktop and narrow mobile layouts were checked. Other browser engines were not separately tested.

## Artwork generation

Created with the built-in image-generation tool, using Ayan’s uploaded portrait as a reference. Final generation prompt:

> Use case: style-transfer. Create a fully stylized cartoon game character based on the attached portrait of Ayan, a young girl. Strongly stylize ALL features into a charming rounded 3D animated children's movie character: oversized expressive hazel-brown eyes, simple sculpted brown hair locks swept to the side and tied in a low ponytail, smooth non-photographic skin, small stylized nose, warm gentle smile, large head and small body, short cartoon limbs. Preserve recognizable eyebrow shape, warm skin, hair color, side part, and face shape from the portrait, and keep the same young age. This must look like a cartoon illustration, NOT a realistic photograph or a photo face on a cartoon body. Full body developer character holding an open purple laptop, navy T-shirt with no logo, teal trousers, purple sneakers. Centered with clear space around head and feet. Transparent background with NO colored glow, NO backdrop, NO shadow haze. One child only, no writing or other characters. Clean polished toy-like 3D render, simple softly rounded shapes.
