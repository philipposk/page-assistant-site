# Page Assistant — website

Marketing + docs site for [Page Assistant](https://github.com/philipposk/page-assistant): an embeddable, grounded, voice-capable assistant that reads any web app and performs real actions, with an `llm.txt` for other agents.

Static site — no build. Open `index.html` or serve the folder.

## Demo video

The two-voice product demo renders from the `demo-pipeline` repo:

```bash
DEMO_URL=https://greenpert.6x7.gr node pipeline.mjs greenpert-assistant --mode=zoom
```

Drop the resulting MP4 at `assets/demo.mp4` (gitignored by default; commit it or host it on a CDN).

## License

MIT © Philippos Kontistakis
