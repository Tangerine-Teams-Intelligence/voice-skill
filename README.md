# voice-skill

> Async voice notes for AI-native teams. Self-hostable. Apache-2.0.

**Status:** Coming v1.7 of [Tangerine](https://github.com/Tangerine-Teams-Intelligence/tma).

## What this will be

A standalone source connector that captures async voice notes from team members (think: Marco Polo for engineering teams) and writes them as structured memory into the team's `memory/threads/` directory.

Hold a hotkey, speak, release → transcribed locally via faster-whisper → appended to memory with frontmatter (speaker, date, topic). Tangerine's daily brief picks it up automatically.

Use cases:
- Solo founder dictates "I just thought of something" without losing context
- Engineer leaves end-of-day update for team in different timezone  
- Any meeting too short to schedule but too important to forget

## Why a separate repo

Voice capture is its own concern with its own dependencies (audio I/O, hotkey libraries). Self-hostable independent of the main Tangerine app.

## Roadmap

- v1.7: First release. CLI + tray icon, push-to-talk hotkey, local Whisper, writes to user's memory dir.
- v1.8: Mobile companion (iOS/Android) for capture-on-the-go.

## License

Apache-2.0. Part of the [Tangerine](https://github.com/Tangerine-Teams-Intelligence/tma) family.
