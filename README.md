# Dad’s Knee Routine

A gentle, illustrated knee-mobility routine PWA made for family use, with seven exercises, a countdown timer, and simple step-by-step controls.

**Try it:** [Open Knee Routine](https://arshcheema4570.github.io/dad-knee-workout/)

## Features

- Seven illustrated exercises with Punjabi and English labels and instructions.
- Start/pause, previous/next, reset, and voice controls.
- Installable PWA with an offline app shell and exercise illustrations.
- No account required. Voice announcements use an offline Kokoro-82M Hindi voice (female, `hf_alpha`) vendored in the repo — about 137 MB downloads once on first voice use, then works offline; if it fails to load, the app falls back to the device's built-in Hindi speech.

## Use and install

Open the deployed link in a modern browser. On a supported phone, use **Install app** or **Add to Home Screen** to install it. After the first successful visit, the app shell and exercise images are cached for offline use.

For local testing, serve the repository root over HTTP, for example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Safety note

This routine is general information, not a diagnosis or personal medical advice. Use a sturdy chair or counter for support. Stop if there is sharp pain, dizziness, chest pain, or a sudden increase in swelling, and ask a doctor or physiotherapist whether the routine is suitable.

## License

The HTML, CSS, and JavaScript code is licensed under the [MIT License](LICENSE). The vendored eSpeak-NG files under `vendor/espeak-ng/` are GPL-3.0 (see `vendor/espeak-ng/LICENSE-espeak-ng`). The father-avatar illustrations and any reference family photographs are personal visual assets and are not covered by that license. Do not reuse them without written permission from Arsh Cheema and the person represented.
