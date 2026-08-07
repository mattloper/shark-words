# Shark Words

Tap-to-hear pronunciations for nine shark-biology terms.

A single self-contained `index.html` — all audio is embedded as base64, so there
are no external requests and it works offline once loaded.

Audio generated locally with [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M)
(Apache-2.0). `sphyrnids` and `carcharhinids` use a pinned phoneme lexicon,
since the default grapheme-to-phoneme pass gets both wrong.
