# WAIQ Privacy Policy

_Last updated: July 2026_

WAIQ is an AI radio host: it plays your music and speaks a short, fact-checked line about each song before it plays. This policy covers what the WAIQ iOS app does with your data.

## No accounts

WAIQ has no sign-in, no user accounts, and no WAIQ-operated servers that store your data. Everything below happens either on your device or as a direct call from your device to the third-party service named.

## What WAIQ stores on your device

- **API keys** (Anthropic, ElevenLabs, and, if you use the alternate Spotify backend, your Spotify Client ID and login tokens) — stored in the iOS Keychain. They never leave your device except to authenticate directly with that provider's own API.
- **Friends & Family roster** — names and details you add for on-air shout-outs, stored locally via SwiftData. Not shared with anyone except as described below.
- **Settings and last-played selection** (playback mode, deck source, shuffle) — stored locally via `UserDefaults`.

## What WAIQ sends to third parties, and why

| Sent to | What | Why |
|---|---|---|
| **Apple Music** (MusicKit) | Playback commands, your library/playlist/station requests | To play music and browse your library — governed by Apple's own privacy policy |
| **Spotify** (alternate backend, optional) | Playback commands, OAuth tokens | Same purpose, if you choose Spotify instead of Apple Music — governed by Spotify's own privacy policy |
| **MusicBrainz** | Song title/artist/album | To look up grounding facts (release info, credits) used in the DJ's commentary |
| **Anthropic (Claude)** | Song title/artist/album, the MusicBrainz facts, and — when relevant — a Friends & Family roster entry | To write the spoken commentary line, including the occasional on-air shout-out |
| **ElevenLabs** (optional, for the lifelike voice) | The generated commentary text | To synthesize it as speech. If no ElevenLabs key is set, speech is synthesized entirely on-device instead, and nothing is sent anywhere for this step |

None of these services receive your name, email, device identifiers, or any account information from WAIQ — only the song and commentary text described above.

## What WAIQ does not do

- No analytics, advertising, or tracking SDKs of any kind.
- No data is sold or shared for advertising purposes.
- No data is collected for a WAIQ-operated server — there isn't one.

## Your choices

- Song commentary (Anthropic) and the lifelike voice (ElevenLabs) are optional — leaving those API keys blank falls back to a built-in line and the on-device iOS voice, respectively.
- You can clear the Friends & Family roster at any time in Settings.
- Removing your API keys from Settings deletes them from the Keychain immediately.

## Contact

Questions about this policy: **johndifini@gmail.com**, or open an issue at [WAIQ-support](https://github.com/johndifini/WAIQ-support).
