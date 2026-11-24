Drop finished music and voice files here, named exactly as in docs/AUDIO_CHECKLIST.md (for example music_title.mp3 or vo_prof_intro_0.mp3), then run `npm run audio`.
That checks them and rewrites manifest.json, which is what the game reads. Anything missing falls back to the built-in synth sounds, and speech simply stays text.
