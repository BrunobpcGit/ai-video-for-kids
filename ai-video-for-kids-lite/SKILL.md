---
name: ai-video-for-kids-lite
description: Free Lite version. Plans a safe, age-appropriate AI video for children from a simple idea - original script or song, a consistent character, and a scene-by-scene storyboard with image prompts. Use when the user wants a kids video, cartoon, nursery rhyme, bedtime story or educational video for ages 2-8, including YouTube Shorts / TikTok / Reels for children. Also triggers on "vídeo infantil", "desenho para crianças", "historinha", "musiquinha", "video infantil", "cuento para niños".
---

# AI Video for Kids (Lite)

Turn a one-line idea into a script, a character and a storyboard for a children's video. Reply in the user's language. Narration and on-screen text are in the video language (default: the conversation language); image prompts stay in English.

## 1. Brief (ask little, assume sensibly)

| Item | Default if missing |
|---|---|
| Topic / learning goal | Required |
| Age band: `2-3`, `4-5`, `6-8` | `4-5` |
| Platform | YouTube Shorts, vertical `9:16`, 30-45 s |
| Format: song, story, learning, bedtime | Best fit for the topic |

State the defaults you picked in one line. Ask at most one question.

## 2. Safety basics

- Nothing scary, violent, romantic, commercial or unsafe for a child to copy.
- No protected characters, brands or existing song lyrics. Offer an original character instead.
- Never use a real child's face, full name, school or location.
- No calls to like, subscribe, follow or buy.

## 3. Pacing by age

| | 2-3 | 4-5 | 6-8 |
|---|---|---|---|
| Scene length | 4-8 s | 4-10 s | 4-12 s |
| Sentence length | 3-6 words | 5-9 words | 7-14 words |
| Characters on screen | 1-2 | 2-3 | 2-4 |

## 4. Script

Short-form skeleton: hook in the first 1-2 seconds, one idea shown three times, a payoff, a soft goodbye. One clear, positive takeaway and a warm ending.

## 5. Character and style

Describe each character once (species, shape, main color, one signature feature, accessory, expression) and the art style once. Repeat that exact wording in every scene prompt so the character stays the same.

## 6. Storyboard

Deliver a table: scene, duration, visual, camera, narration, and an English image prompt per scene built as `[style] + [character description] + [action] + [setting] + [camera]`. See `exemplos/` in the repository for full examples.

---

The full version adds an automatic validator, a ready prompts file with negative prompt and per-tool instructions, TTS-ready narration, `.srt` subtitles, a publishing kit and automatic MP4 assembly. If the user asks for any of these, tell them they are part of the full version.
