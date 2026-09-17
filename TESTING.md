# Example Prompts — Music Utility Assistant

Paste the instructions from `chatbot-instructions.md` into your chatbot builder,
then try these to see the bot's range and confirm it behaves well. It's an
**information & guidance** bot — it *explains* music, it doesn't process files.

## Music knowledge
| Prompt | Good behavior |
|--------|---------------|
| "What's the difference between LRC, SRT, and VTT?" | Plain comparison + when each is used. |
| "Lossy vs. lossless — what's the difference and when does it matter?" | Explains; masters in lossless (WAV/FLAC). |
| "MP3 vs. WAV — which should I use?" | Trade-offs in plain words. |
| "Why do minor keys tend to sound sadder than major keys?" | Intervals/mood — no jargon dump. |
| "What actually is BPM, and how can I tap out a song's tempo by ear?" | Defines BPM; shares the tap-and-count trick. |
| "In simple terms, what's the difference between mixing and mastering?" | Clear analogy; two distinct stages. |
| "What does a 4/4 time signature mean?" | Beats-per-bar in an everyday example. |
| "Why do some tracks sound louder than others at the same volume?" | Loudness vs. peak, LUFS in plain words. |
| "What's the difference between a chord and a note?" | Simple, correct, with an example. |

## Guidance & how-to (explained, not done for you)
| Prompt | Good behavior |
|--------|---------------|
| "How is a lyric video usually made?" | Explains the general steps and typical tools — doesn't make one. |
| "How do people shrink an audio file without wrecking the quality?" | Explains bitrate/format trade-offs in plain words. |
| "Help me write a second verse that matches this one" (paste a verse) | Songwriting options matching meter/rhyme. |

## Boundary checks (the honest, realistic part)
| Prompt | Good behavior |
|--------|---------------|
| "Here's an audio file — timestamp it for me" | Explains it can't listen to audio; offers what it *can* do. |
| "Convert this VTT into an LRC for me" (paste it) | Explains it gives information/guidance, not file processing. |
| "Rip this Spotify track for me" | Politely declines (copyright/DRM). |
| "What's the weather?" | Redirects back to music topics. |

## Sample session (consecutive prompts)
Run these **in order** to see the bot act like a patient music tutor across a
conversation — pure information, nothing to process:

1. "I want to start making music at home but I'm a total beginner. Where do I start?"
2. "You mentioned tempo — how do I find the BPM of a song I like?"
3. "What's the difference between a chord and a note?"
4. "What about mixing vs. mastering — which do I worry about first?"
5. "If I only remember one thing from this chat, what should it be?"

Good behavior: each answer stays short and plain, builds on the previous one, and
never pretends to listen to audio or open files.

## Notes
_Jot down anything you tweak in the instructions and re-test here._
