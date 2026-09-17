# Music Utility Assistant

A **BoodleBox chatbot** that helps with the practical side of music — a controlled,
text-based assistant that explains audio/lyric concepts and performs real
text utilities in chat.

## What it does
- **Explains** audio, lyric, and subtitle concepts in plain language (formats,
  bitrate/sample rate, LRC vs. SRT vs. VTT, word-level timestamps, BPM/key, etc.).
- **Converts & reformats** text you paste — SRT ⇄ VTT ⇄ LRC ⇄ plain text, builds LRC
  from lyrics + times, shifts/scales timestamps, cleans up lyric files.
- **Generates commands & workflows** — ready-to-run `ffmpeg`/Audacity recipes for
  converting, trimming, extracting, or normalizing audio, with each step explained.
- **Helps create content** — drafting/editing lyrics, song structure, metadata.

It's **honest about its limits**: it can't listen to audio, process real files, or
access the internet — it works with text and know-how, and hands you the commands to
run yourself. It also won't help with piracy or copyright circumvention.

## Files
| File | Purpose |
|------|---------|
| [`chatbot-instructions.md`](chatbot-instructions.md) | The chatbot's instructions. Copy the **INSTRUCTIONS** section into the BoodleBox builder. |
| [`TESTING.md`](TESTING.md) | Example prompts for exercising the bot. |
| [`CLAUDE.md`](CLAUDE.md) | Working preferences Claude Code reads in this folder. |

## Use it in BoodleBox
1. Open `chatbot-instructions.md` and copy the **INSTRUCTIONS (paste this into
   BoodleBox)** section.
2. Create a new chatbot in BoodleBox and paste it into the instructions field.
3. Name it **Music Utility Assistant** and start chatting (see `TESTING.md` for
   prompts to try).
