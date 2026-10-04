# WAIQ Privacy Policy

_Last updated: October 3, 2026_

WAIQ is an AI radio host. It plays your Apple Music and, as each song starts, speaks a short line about it. This policy covers what the WAIQ iOS app does with your data.

## The short version

- WAIQ has no accounts, no analytics, no ads, and no WAIQ-operated servers. The developer never receives your data.
- With the default setup, the DJ's lines are written on your iPhone by Apple Intelligence and spoken by a voice that runs on your iPhone. The only things that leave your phone are song titles and artists, sent to look up facts about each song.
- The optional AI services (Anthropic, OpenAI and ElevenLabs) are off until you add your own API key for one of them. WAIQ asks for your permission when you add a key, and removing the key withdraws that permission.

## No accounts

WAIQ has no sign-in and no WAIQ servers. Everything below happens either on your iPhone or as a direct request from your iPhone to the service named.

## What WAIQ keeps on your iPhone

- **API keys** you add (Anthropic, OpenAI, ElevenLabs), stored in the iOS Keychain. A key is sent only to its own provider, to sign your requests.
- **Friends & Family roster**: the names, relationships, birth years and notes you add for on-air shout-outs.
- **Your 👍/👎 ratings** of DJ lines, and a cache of lines already written for songs you've played.
- **Settings**: your playlist or station, DJ brain, voice, location-facts choice, and your answers to the permission prompts.
- **A diagnostic log** of errors and session events, and a file of generated lines and ratings used to improve WAIQ's built-in lines. The log records song names and app events; the field-data file contains no API keys or roster details. Neither leaves your phone unless you tap **Share** in Settings and choose where to send it.

To remove everything, clear your API keys in Settings, then delete the app.

## What WAIQ sends, to whom, and when

| Sent to | What | When |
|---|---|---|
| **Apple Music** | Playback commands and requests for your library, playlists, stations and song details | Always, to play music. Governed by Apple's privacy policy |
| **Apple Intelligence** | Nothing leaves your phone: the on-device model writes the DJ's lines locally | When the on-device DJ brain is in use (the default where available) |
| **MusicBrainz** | Song title, artist and album | Each song, to look up release facts |
| **Wikipedia** | Song title and artist | Each song, to look up the song's story |
| **Wikipedia** | Your coordinates | Only if you turn on **location facts**, to find notable nearby places |
| **Apple (geocoding)** | Your coordinates, to name the town or area you're in | Only if you turn on location facts. Governed by Apple's privacy policy |
| **Anthropic (Claude)** | Song title, artist and album; facts found about it; lines you rated 👍/👎; and, for shout-outs, Friends & Family names, relationships, ages and notes. With location facts on, also your town, region and country, nearby landmark names, facts about them, and whether you're walking, running or driving (never your coordinates) | Only if you add an Anthropic API key and agree to the permission prompt |
| **OpenAI** | The same song, rating and Friends & Family details as Anthropic (no location) | Only if you add an OpenAI API key, choose the OpenAI brain, and agree to the permission prompt |
| **ElevenLabs** | The text of each DJ line, which may include a Friends & Family name | Only if you add an ElevenLabs API key and agree to the permission prompt. Without a key, the voice runs entirely on your iPhone and sends nothing |

When you use your own API key, the request goes to your account with that provider, under that provider's terms and privacy policy, including how long it keeps data. WAIQ doesn't control that and never sees it. Before adding a key, read the provider's policy: [Anthropic](https://www.anthropic.com/legal/privacy), [OpenAI](https://openai.com/policies/privacy-policy), [ElevenLabs](https://elevenlabs.io/privacy-policy).

Your location and motion are used only while WAIQ is on air with location facts turned on. Location facts are off by default.

## Spotify

Spotify isn't available in current versions of WAIQ. If it returns, this policy will be updated first.

## What WAIQ does not do

- No analytics, advertising or tracking SDKs.
- No selling or sharing of data for advertising.
- No collection on a WAIQ-operated server, because there isn't one.

## Your choices

- **Remove an API key** in Settings to stop sending data to that service. The key is deleted from the Keychain immediately, and adding a key again asks for permission again.
- **Turn location facts off** in Settings, or turn off WAIQ's Location and Motion access in iOS Settings.
- **Edit or clear the Friends & Family roster** at any time in Settings.

## Children

WAIQ isn't directed to children under 13 and doesn't knowingly collect their personal information. Roster entries you add about family members stay on your phone unless you turn on an AI service as described above.

## Changes

When this policy changes, the date at the top changes. Before WAIQ sends your data to a service in a new way, it will ask for your permission again.

## Contact

Questions about this policy: **johndifini@gmail.com**, or open an issue at [WAIQ-support](https://github.com/johndifini/WAIQ-support).
