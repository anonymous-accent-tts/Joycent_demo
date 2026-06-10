# Joycent Demo

Static GitHub Pages demo for Joycent audio samples.

## Update Audio

Current audio files are copied from `../slt_demo` according to `../demo.txt`.
The page currently loads:

- `assets/audio/macst` for SSB0693 rows only
- `assets/audio/joycent`
- `assets/audio/encoder`
- `assets/audio/decoder`
- `assets/audio/decoder_only`

`assets/audio/cosyvoice` can be added later if those wav files become available.
The corresponding column already exists in `index.html`.

The `A0002_S001_0_G0004_segment_0023` rows currently do not show Joycent audio
because `../slt_demo/joycent` does not contain the matching wav files.

## Update Paper Content

Replace the title, abstract, and `assets/img/model-placeholder.svg` with the
final paper title, abstract, and model architecture figure.
