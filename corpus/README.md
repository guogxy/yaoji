# Public textual corpus

This directory contains only the distributed classical text and modern editorial
readings, not personal records or the application source code.

- `zhouyi.json`: 64 hexagrams, bottom-first lines, Tuan and Image passages, with
  fixed Wikisource revision links identifying the source and contributor history.
- `hexagram-readings.json`: modern editorial readings for the 64 hexagrams.
- `line-readings.json`: all 384 line readings, including reference titles and URLs.

Ancient underlying texts are public domain. Wikisource transcription/editorial
contributions and YaoJi's compiled-data adaptations and AI-assisted editorial
readings are provided under CC BY-SA 4.0. Modern readings are not quotations from
the historical authors or from contemporary teachers. See
`../licenses/ZhouYi-NOTICE.txt` for attribution, changes and license links.

The full line catalog is exported from the app's validated catalog using the
`testPublicLineCorpusRoundTripsWithoutPrivateRecords` test and the explicit
`YAOJI_CORPUS_EXPORT` output path. It contains no case library or user data.
